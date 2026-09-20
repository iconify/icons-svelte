<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgrfb-bqu"/><path class="qnmmmsbha"/><path class="klk7mdb2c"/><path class="h0co0sh-j"/><path class="ys-dg812g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tombstone-outline-thin" {...props}></Icon>
<style>
:global(.h0co0sh-j) {
  d: path("m20.5 9.5 -3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.klk7mdb2c) {
  d: path("m17.5 9.5 3 3");
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
