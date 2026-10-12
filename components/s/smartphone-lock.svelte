<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="t_2lkqbxb"><g mask="url(#SVGsZ1vtcCp)"><rect class="e3xg4r4ds"/></g><rect class="tk08jrbzk"/><path class="u46xc4iak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:smartphone-lock" {...props}></Icon>
<style>
:global(.e3xg4r4ds) {
  width: 12.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.jf0axzbmx) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.t_2lkqbxb) {
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tk08jrbzk) {
  width: 5.5px;
  height: 4px;
  x: 14.75px;
  y: 17px;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.u46xc4iak) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 17v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
