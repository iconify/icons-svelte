<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/v/vwkut_xdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGFXPcogNM" x1="256" x2="256" y1="0" y2="512" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGFXPcogNM)" class="vwkut_xdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yacreaderlibrary-light" {...props}></Icon>
