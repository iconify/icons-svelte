<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_159j0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1534,"height":1536};
const content = `<path class="pv_159j0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-direction-sw" {...props}></Icon>
