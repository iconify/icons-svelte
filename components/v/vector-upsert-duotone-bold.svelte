<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sw_hwrbxs"/><path class="v2mnclz8q"/><path class="wa9pjob9g"/><path class="zoomnj6dr"/><path class="knb00ei4h"/><path class="d_b1a31kv"/><path class="bk6uwfbvv"/><path class="slz7u0oyn"/><path class="d69_otb1b"/><path class="scs5jbhoc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vector-upsert-duotone-bold" {...props}></Icon>
<style>
:global(.bk6uwfbvv) {
  d: path("M5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.d_b1a31kv) {
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.d69_otb1b) {
  d: path("M18 4v6");
}

:global(.knb00ei4h) {
  d: path("M5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.scs5jbhoc) {
  d: path("m15 7 3 3 3 -3");
}

:global(.slz7u0oyn) {
  d: path("M2 19.5A2.5 2.5 0 0 1 4.5 17h15a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-15A2.5 2.5 0 0 1 2 19.5");
}

:global(.sw_hwrbxs) {
  fill: currentColor;
  d: path("M5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.v2mnclz8q) {
  fill: currentColor;
  d: path("M10 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wa9pjob9g) {
  fill: currentColor;
  d: path("M5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zoomnj6dr) {
  fill: currentColor;
  d: path("M2 19.5A2.5 2.5 0 0 1 4.5 17h15a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-15A2.5 2.5 0 0 1 2 19.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
