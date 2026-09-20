<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xvl0zubxy"/><path class="ze6_11znx"/><path class="fizmkteml"/><path class="g8vjt7b7p"/><path class="h9piesnqy"/><path class="r7dhdp-mq"/><path class="umr6jbb1c"/><path class="j7phtvv5f"/><path class="ceatt7y_b"/><path class="zmj1nccll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:snap-grid-duotone-bold" {...props}></Icon>
<style>
:global(.ceatt7y_b) {
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.fizmkteml) {
  fill: currentColor;
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g8vjt7b7p) {
  fill: currentColor;
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h9piesnqy) {
  fill: currentColor;
  d: path("M8.5 10.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j7phtvv5f) {
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.r7dhdp-mq) {
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.umr6jbb1c) {
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xvl0zubxy) {
  fill: currentColor;
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ze6_11znx) {
  fill: currentColor;
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zmj1nccll) {
  d: path("M8.5 10.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
