<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqdnidbra.css';
import '../../css/z/zkw9hjbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqdnidbra"/><path class="zkw9hjbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:threadfin-dark" {...props}></Icon>
