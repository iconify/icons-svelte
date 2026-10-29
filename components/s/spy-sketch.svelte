<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eab5obbwx.css';
import '../../css/s/s0a204b1r.css';
import '../../css/y/ysas-lb9p.css';
import '../../css/l/le_23rbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eab5obbwx"/><path class="s0a204b1r wm-k"/><path class="wm-k ysas-lb9p"/><path class="le_23rbrp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:spy-sketch" {...props}></Icon>
