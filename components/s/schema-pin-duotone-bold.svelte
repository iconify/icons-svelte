<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="whb7_bbil"/><path class="dpra8nb8c"/><path class="hk-jkdb0v"/><path class="ah8uvpf1o"/><path class="e6q34etyy"/><path class="g22ksobnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:schema-pin-duotone-bold" {...props}></Icon>
<style>
:global(.ah8uvpf1o) {
  d: path("M3 10h13");
}

:global(.dpra8nb8c) {
  fill: currentColor;
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e6q34etyy) {
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.g22ksobnl) {
  d: path("M19 14v4");
}

:global(.hk-jkdb0v) {
  d: path("M3 8a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.whb7_bbil) {
  fill: currentColor;
  d: path("M3 8a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
