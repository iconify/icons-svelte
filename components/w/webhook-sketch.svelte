<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mey_bqu0u.css';
import '../../css/t/t8w3xju4u.css';
import '../../css/h/h7v3tlb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mey_bqu0u wm-k"/><path class="t8w3xju4u wm-k"/><path class="h7v3tlb3w wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:webhook-sketch" {...props}></Icon>
