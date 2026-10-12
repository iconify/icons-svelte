<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="kf_mvwa8r"/><rect class="g84v2sbim"/><path class="x0xvuj0sw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:user-guest" {...props}></Icon>
<style>
:global(.g84v2sbim) {
  width: 5px;
  height: 6px;
  x: 16px;
  y: 10.5px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kf_mvwa8r) {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75");
}

:global(.rknchmb5r) {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

:global(.x0xvuj0sw) {
  d: path("m17.25 10.5l-.75-3m3.25 3l.75-3");
}

</style>
