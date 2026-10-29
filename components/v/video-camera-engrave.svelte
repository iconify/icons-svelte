<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pnl3qq6dw.css';
import '../../css/h/h-88fv_ot.css';
import '../../css/l/liwxtwofv.css';
import '../../css/z/za3dt0bho.css';
import '../../css/r/rcb7clbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pnl3qq6dw wm-k"/><path class="h-88fv_ot wm-a"/><path class="liwxtwofv wm-shadow"/><path class="wm-k za3dt0bho"/><path class="rcb7clbki wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:video-camera-engrave" {...props}></Icon>
