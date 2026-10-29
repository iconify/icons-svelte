<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r1x5901qb.css';
import '../../css/c/c8btfjb_a.css';
import '../../css/z/zvbq_yb6b.css';
import '../../css/c/cfmykrbut.css';
import '../../css/f/fjsedw-yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r1x5901qb wm-k"/><path class="c8btfjb_a wm-a"/><path class="wm-shadow zvbq_yb6b"/><path class="cfmykrbut wm-k"/><path class="fjsedw-yo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:test-tube-engrave" {...props}></Icon>
