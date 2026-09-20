<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnkwk-b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnkwk-b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vrchat" {...props}></Icon>
