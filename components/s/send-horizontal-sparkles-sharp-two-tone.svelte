<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/znmg3kb4h.css';
import '../../css/i/i787-pb0p.css';
import '../../css/k/k6tsawspk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="znmg3kb4h"/><path class="i787-pb0p"/><path class="k6tsawspk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:send-horizontal-sparkles-sharp-two-tone" {...props}></Icon>
