<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qvk5q1f0x.css';
import '../../css/x/xlmfdgbol.css';
import '../../css/y/yyeasgwwc.css';
import '../../css/h/h65e0tmly.css';
import '../../css/s/s53tgbb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qvk5q1f0x wm-k"/><path class="wm-a xlmfdgbol"/><path class="wm-shadow yyeasgwwc"/><path class="h65e0tmly wm-k"/><path class="s53tgbb5w wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:split-engrave" {...props}></Icon>
