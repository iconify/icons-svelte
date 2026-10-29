<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nfsx06xba.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/s/sxlrsnbic.css';
import '../../css/k/kk0onebow.css';
import '../../css/a/aq_2o7bhr.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nfsx06xba wm-k"/><path class="ol-kpp5cg wm-s"/><path class="sxlrsnbic wm-shadow"/><path class="kk0onebow wm-k"/><path class="aq_2o7bhr wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:server-off-engrave" {...props}></Icon>
