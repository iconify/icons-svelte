<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e28ifp_ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e28ifp_ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:time-5" {...props}></Icon>
