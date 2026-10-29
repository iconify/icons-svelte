<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/luw39ft7l.css';
import '../../css/x/xh1b6ubxr.css';
import '../../css/t/ti18yabmh.css';
import '../../css/t/t0axcbk6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="luw39ft7l"/><path class="wm-a xh1b6ubxr"/><path class="ti18yabmh"/><path class="t0axcbk6e wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sleigh-duo" {...props}></Icon>
