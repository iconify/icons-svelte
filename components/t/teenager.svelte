<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pi_kljilo"/><circle class="aj6v90bht"/><path class="wzd42obmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:teenager" {...props}></Icon>
<style>
:global(.aj6v90bht) {
  cx: 12px;
  cy: 9.75px;
  r: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pi_kljilo) {
  d: path("M3.75 20.25h16.5a1 1 0 0 0 1-1v-.75c0-2.1-1.5-3.9-3.75-4.75v-4a5.5 5.5 0 0 0-11 0v4c-2.25.85-3.75 2.65-3.75 4.75v.75a1 1 0 0 0 1 1");
}

:global(.wzd42obmw) {
  d: path("M10.5 15.25v2.5m3-2.5v2.5");
}

</style>
