<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/z12vwrbxv.css';
import '../../css/q/qtv_cddoq.css';
import '../../css/y/yrrgw6qvv.css';
import '../../css/h/hi4mwm5qt.css';
import '../../css/h/hup0fn6ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco z12vwrbxv"/><path class="qtv_cddoq wm-deco"/><path class="wm-deco yrrgw6qvv"/><path class="hi4mwm5qt"/><path class="hup0fn6ni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wrench-blueprint" {...props}></Icon>
