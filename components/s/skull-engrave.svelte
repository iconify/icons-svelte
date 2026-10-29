<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a0npckbak.css';
import '../../css/w/wp_raccwx.css';
import '../../css/x/xtomtqpdh.css';
import '../../css/t/tjbgnmb3g.css';
import '../../css/y/yzbkkhbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a0npckbak wm-k"/><path class="wm-a wp_raccwx"/><path class="wm-shadow xtomtqpdh"/><path class="tjbgnmb3g wm-k"/><path class="wm-a yzbkkhbwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skull-engrave" {...props}></Icon>
