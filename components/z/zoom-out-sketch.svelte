<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wnzp-ncyf.css';
import '../../css/x/x7annnbrx.css';
import '../../css/q/qktlr5byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wnzp-ncyf"/><path class="wm-k x7annnbrx"/><path class="qktlr5byx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zoom-out-sketch" {...props}></Icon>
