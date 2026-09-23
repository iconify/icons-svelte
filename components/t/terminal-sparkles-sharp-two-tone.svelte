<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/lb1jov5wm.css';
import '../../css/k/koo-sesdl.css';
import '../../css/q/q4td3mb4p.css';
import '../../css/r/rhu4n0brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lb1jov5wm"/><path class="koo-sesdl"/><path class="q4td3mb4p"/><path class="rhu4n0brl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal-sparkles-sharp-two-tone" {...props}></Icon>
