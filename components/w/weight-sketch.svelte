<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cony-fkuc.css';
import '../../css/o/opbxnxbxe.css';
import '../../css/u/uex_d5bbi.css';
import '../../css/w/w3sy0kb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cony-fkuc"/><path class="opbxnxbxe wm-a"/><path class="uex_d5bbi wm-k"/><path class="w3sy0kb_n wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:weight-sketch" {...props}></Icon>
