<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oo2qfubvl.css';
import '../../css/r/rtpnq8b2m.css';
import '../../css/u/u8u1igx1h.css';
import '../../css/h/h-mw_xb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oo2qfubvl"/><path class="rtpnq8b2m"/><path class="u8u1igx1h"/><path class="h-mw_xb8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruler-pen-line-duotone" {...props}></Icon>
