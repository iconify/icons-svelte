<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f6jp3jbsz.css';
import '../../css/z/zclo0mbka.css';
import '../../css/y/y2k4rub5q.css';
import '../../css/s/st-oxhb_e.css';
import '../../css/x/xnnn3ac7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f6jp3jbsz wm-k"/><path class="wm-a zclo0mbka"/><path class="wm-shadow y2k4rub5q"/><path class="st-oxhb_e wm-k"/><path class="wm-a xnnn3ac7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:volume-engrave" {...props}></Icon>
