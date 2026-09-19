<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/aqtyesbwn.css';
import '../../css/q/qr90g_bcv.css';
import '../../css/e/ewsav27ph.css';
import '../../css/f/fago-0h9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="aqtyesbwn"/><path class="qr90g_bcv"/><circle class="ewsav27ph"/><path class="fago-0h9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:tip-jar-outline" {...props}></Icon>
