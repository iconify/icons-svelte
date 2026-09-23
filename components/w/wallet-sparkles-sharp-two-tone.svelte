<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/x41mlqjoc.css';
import '../../css/x/xhj1trd8o.css';
import '../../css/j/j_9swybeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x41mlqjoc"/><path class="xhj1trd8o"/><path class="j_9swybeu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wallet-sparkles-sharp-two-tone" {...props}></Icon>
