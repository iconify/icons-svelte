<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/alk7dvb9p.css';
import '../../css/m/md1698vtm.css';
import '../../css/q/qg4ud0b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="alk7dvb9p"/><path class="md1698vtm"/><path class="qg4ud0b0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tag-horizontal-start-percent-sharp-two-tone" {...props}></Icon>
