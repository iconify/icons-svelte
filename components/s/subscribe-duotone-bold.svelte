<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fizmkteml"/><path class="by-tgtbuj"/><path class="g69jaac1i"/><path class="j7phtvv5f"/><path class="p-74fg5cj"/><path class="vz5_16nyg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:subscribe-duotone-bold" {...props}></Icon>
<style>
:global(.by-tgtbuj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12a7 7 0 0 1 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fizmkteml) {
  fill: currentColor;
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g69jaac1i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 6a13 13 0 0 1 13 13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j7phtvv5f) {
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p-74fg5cj) {
  d: path("M5 12a7 7 0 0 1 7 7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vz5_16nyg) {
  d: path("M5 6a13 13 0 0 1 13 13");
}

</style>
