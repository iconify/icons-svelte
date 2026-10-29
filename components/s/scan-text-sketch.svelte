<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l8807ublx.css';
import '../../css/f/f91jueh9c.css';
import '../../css/l/lzvbhobgb.css';
import '../../css/i/i-xuwwzrm.css';
import '../../css/r/rxw6t9p2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l8807ublx"/><path class="f91jueh9c wm-k"/><path class="lzvbhobgb wm-a"/><path class="i-xuwwzrm wm-k"/><path class="rxw6t9p2o wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scan-text-sketch" {...props}></Icon>
