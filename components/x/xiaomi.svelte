<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri9w4fyml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri9w4fyml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xiaomi" {...props}></Icon>
