<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="pty_wsbvs"/><path class="alb65s2_r"/><path class="xttphobcs"/><path class="gjtpdgbwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:typosquat-outline-bold" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.alb65s2_r) {
  d: path("M8 13h3.5");
}

:global(.gjtpdgbwb) {
  d: path("m16 11.5 -3 3");
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xttphobcs) {
  d: path("m13 11.5 3 3");
}

</style>
