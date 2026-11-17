<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxk4r1_gb.css';
import '../../css/b/bfgj_tbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gxk4r1_gb"/><path class="bfgj_tbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vpn-sentinel-light" {...props}></Icon>
