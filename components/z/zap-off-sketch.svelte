<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ei9be55ro.css';
import '../../css/k/kc3tbqb7h.css';
import '../../css/w/wgkyg6fmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ei9be55ro wm-k"/><path class="kc3tbqb7h wm-k"/><path class="wgkyg6fmx wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zap-off-sketch" {...props}></Icon>
