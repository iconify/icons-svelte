<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj4sx_wkb.css';
import '../../css/i/ipyyj6ggt.css';
import '../../css/s/sun_m7tdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mj4sx_wkb"/><path class="ipyyj6ggt"/><path class="sun_m7tdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:watchtower-light" {...props}></Icon>
