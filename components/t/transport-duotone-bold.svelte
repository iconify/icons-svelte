<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgscl2bdj"/><path class="mypzt1bhf"/><path class="e2d7kob3q"/><path class="fepp1_bmx"/><path class="ombslrhta"/><path class="dezc-zb_n"/><path class="zirb-hbnv"/><path class="n0hr0gbrt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transport-duotone-bold" {...props}></Icon>
<style>
:global(.dezc-zb_n) {
  d: path("M2 16.5h20");
}

:global(.e2d7kob3q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 7.5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fepp1_bmx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16.5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mypzt1bhf) {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0hr0gbrt) {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ombslrhta) {
  d: path("M2 7.5h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xgscl2bdj) {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zirb-hbnv) {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
