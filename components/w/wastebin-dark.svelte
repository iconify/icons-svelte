<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fef2p4b2l.css';
import '../../css/r/r2rl9cbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGx4Gp1bCt" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="fef2p4b2l"/><stop offset="1"/></linearGradient><path fill="url(#SVGx4Gp1bCt)" class="r2rl9cbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wastebin-dark" {...props}></Icon>
