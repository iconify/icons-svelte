<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nllqmxtta.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/j/jtojvkpsm.css';
import '../../css/h/hdnmcyb1z.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nllqmxtta wm-k"/><path class="ol-kpp5cg wm-s"/><path class="jtojvkpsm wm-shadow"/><path class="hdnmcyb1z wm-k"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-off-engrave" {...props}></Icon>
