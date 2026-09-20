<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x50q_4bdr"/><path class="o2uaggb1q"/><path class="ehef6tbzw"/><path class="mf-afdped"/><path class="jg5k_rbda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:significance-outline-bold" {...props}></Icon>
<style>
:global(.ehef6tbzw) {
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jg5k_rbda) {
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mf-afdped) {
  d: path("M15 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.o2uaggb1q) {
  d: path("M5 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>
