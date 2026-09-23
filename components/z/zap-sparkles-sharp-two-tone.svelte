<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/lvgzmebcf.css';
import '../../css/v/vy-nx7bhq.css';
import '../../css/s/skqfcdqhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lvgzmebcf"/><path class="vy-nx7bhq"/><path class="skqfcdqhg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:zap-sparkles-sharp-two-tone" {...props}></Icon>
