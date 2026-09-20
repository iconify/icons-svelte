<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c18e-5bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c18e-5bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:triangle-outline" {...props}></Icon>
