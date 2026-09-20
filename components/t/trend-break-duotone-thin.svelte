<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1inv7bvp"/><path class="lhe0hab7a"/><path class="bt_2bvgpa"/><path class="oatlkcbwl"/><path class="uj_hf0zyk"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trend-break-duotone-thin" {...props}></Icon>
<style>
:global(.a1inv7bvp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 15 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lhe0hab7a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 9 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oatlkcbwl) {
  d: path("m3 15 8 -8");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.uj_hf0zyk) {
  d: path("m13 9 6 6");
}

</style>
