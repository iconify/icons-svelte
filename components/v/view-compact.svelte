<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i301vq99h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="i301vq99h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-compact" {...props}></Icon>
