<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk0phibge.css';
import '../../css/o/ozfgr-c4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rk0phibge"/><path class="ozfgr-c4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synclyrics-dark" {...props}></Icon>
