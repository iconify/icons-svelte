<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpeggtb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xpeggtb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:superscript" {...props}></Icon>
