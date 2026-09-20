<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyvm7xbin"/><path class="lo7kp72nh"/><path class="ze3njkbee"/><path class="t47xolklb"/><path class="o9qd50bgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:swimming-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lo7kp72nh) {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.o9qd50bgb) {
  d: path("M2 18h3l3 -3 3 3 3 -3 3 3h5");
}

:global(.t47xolklb) {
  d: path("M9 11h8");
}

:global(.yyvm7xbin) {
  fill: currentColor;
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ze3njkbee) {
  d: path("m9 10 4 -4");
}

</style>
