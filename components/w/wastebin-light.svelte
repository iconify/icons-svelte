<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-llkv2cb.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/r/r2rl9cbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGpZrfYbPV" x1="0" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGpZrfYbPV)" class="r2rl9cbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wastebin-light" {...props}></Icon>
