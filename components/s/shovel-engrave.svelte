<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q5y09vy-a.css';
import '../../css/s/s6px0bc7e.css';
import '../../css/i/i6m159bpq.css';
import '../../css/f/fjzpsmbxy.css';
import '../../css/x/xkg1wybgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q5y09vy-a wm-k"/><path class="s6px0bc7e wm-a"/><path class="i6m159bpq wm-shadow"/><path class="fjzpsmbxy wm-k"/><path class="wm-a xkg1wybgt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shovel-engrave" {...props}></Icon>
