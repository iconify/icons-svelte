<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ebtl3ogzn"/><path class="fctby995g"/><circle class="mi5v6ubzt"/><path class="nlkra7b2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wrestling" {...props}></Icon>
<style>
:global(.ebtl3ogzn) {
  cx: 5.25px;
  cy: 6px;
  r: 1.75px;
}

:global(.fctby995g) {
  d: path("M3.25 21.25L5.5 15.5L7 10.25l5 3.25m-5-3.25l4.5-1.5m-6 6.75l3 5.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mi5v6ubzt) {
  cx: 18.75px;
  cy: 6px;
  r: 1.75px;
}

:global(.nlkra7b2v) {
  d: path("M20.75 21.25L18.5 15.5L17 10.25l-5 3.25m5-3.25l-4.5-1.5m6 6.75l-3 5.75");
}

</style>
