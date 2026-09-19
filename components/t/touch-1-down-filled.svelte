<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp8-mcbwg.css';
import '../../css/n/nd-6u87gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rp8-mcbwg"/><path class="nd-6u87gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:touch-1-down-filled" {...props}></Icon>
