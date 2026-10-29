<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eaj_p_cdz.css';
import '../../css/n/ndixsabmg.css';
import '../../css/c/ccht0bp_w.css';
import '../../css/l/lw875-p4x.css';
import '../../css/p/ps9k3gbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eaj_p_cdz wm-k"/><path class="ndixsabmg wm-a"/><path class="ccht0bp_w wm-shadow"/><path class="lw875-p4x wm-k"/><path class="ps9k3gbsc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:upload-engrave" {...props}></Icon>
