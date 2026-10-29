<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cpt_bn45o.css';
import '../../css/y/yf__y5x2v.css';
import '../../css/e/e-vt1mrhx.css';
import '../../css/y/yy1kui28t.css';
import '../../css/o/of1s15oee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cpt_bn45o"/><path class="wm-k yf__y5x2v"/><path class="e-vt1mrhx wm-k"/><path class="wm-a yy1kui28t"/><path class="of1s15oee wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-lock-sketch" {...props}></Icon>
