<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rbpy15bdk.css';
import '../../css/u/uvsyy_17f.css';
import '../../css/q/qc8g0bcwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rbpy15bdk"/><path class="uvsyy_17f wm-k"/><path class="qc8g0bcwg wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ticket-sketch" {...props}></Icon>
