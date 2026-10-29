<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jbeiewgbz.css';
import '../../css/o/ogu_r4rwb.css';
import '../../css/q/qntre5byd.css';
import '../../css/y/yb05owbgu.css';
import '../../css/g/g0hitnb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jbeiewgbz"/><path class="ogu_r4rwb wm-k"/><path class="qntre5byd wm-a"/><path class="wm-k yb05owbgu"/><path class="g0hitnb-s wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trees-sketch" {...props}></Icon>
