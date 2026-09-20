<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqdnidbra.css';
import '../../css/p/ps2d02mlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqdnidbra"/><path class="ps2d02mlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:threadfin-dark" {...props}></Icon>
