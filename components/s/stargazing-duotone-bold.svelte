<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hyxl6qb3t"/><path class="e63e9dbag"/><path class="nz7_80v_q"/><path class="lb4oz-s5s"/><path class="rcodo-bcu"/><path class="znfuzdoyp"/><path class="mt0duqbnk"/><path class="luzoskb2e"/><path class="l1lmw_bdv"/><path class="saj3disjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stargazing-duotone-bold" {...props}></Icon>
<style>
:global(.e63e9dbag) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hyxl6qb3t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l1lmw_bdv) {
  d: path("M13 11h6");
}

:global(.lb4oz-s5s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.luzoskb2e) {
  d: path("M16 8v6");
}

:global(.mt0duqbnk) {
  d: path("M4 6h6");
}

:global(.nz7_80v_q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rcodo-bcu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20c4 -3 14 -3 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.saj3disjq) {
  d: path("M3 20c4 -3 14 -3 18 0");
}

:global(.znfuzdoyp) {
  d: path("M7 3v6");
}

</style>
