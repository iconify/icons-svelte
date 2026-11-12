<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj4sx_wkb.css';
import '../../css/v/vp08acc_f.css';
import '../../css/k/kpqed-bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mj4sx_wkb"/><path class="vp08acc_f"/><path class="kpqed-bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:watchtower-light" {...props}></Icon>
