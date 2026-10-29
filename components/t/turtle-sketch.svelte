<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g1-dnh7xo.css';
import '../../css/m/mdr1krqpu.css';
import '../../css/u/uaprxrdhx.css';
import '../../css/v/vs4f-zb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g1-dnh7xo"/><path class="mdr1krqpu wm-k"/><path class="uaprxrdhx"/><path class="vs4f-zb2g wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:turtle-sketch" {...props}></Icon>
