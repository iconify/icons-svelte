<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jg727-bmc.css';
import '../../css/c/c3tq19bps.css';
import '../../css/r/rnno1ib4f.css';
import '../../css/t/t1wdvofuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jg727-bmc"/><path class="c3tq19bps wm-s"/><path class="rnno1ib4f wm-k"/><path class="t1wdvofuo wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smartphone-charging-sketch" {...props}></Icon>
