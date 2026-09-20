<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j5hk4ybky"/><path class="z8ojisy5e"/><path class="h51gqww2n"/><path class="wquo_ibsk"/><path class="f8n4gobtp"/><path class="mc3x0bbgo"/><path class="w9rzo5b1c"/><path class="lgk47ib7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:time-difference-duotone-thin" {...props}></Icon>
<style>
:global(.f8n4gobtp) {
  d: path("M6.5 12h3");
}

:global(.h51gqww2n) {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j5hk4ybky) {
  fill: currentColor;
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lgk47ib7d) {
  d: path("M14.5 12h3");
}

:global(.mc3x0bbgo) {
  d: path("M13 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.w9rzo5b1c) {
  d: path("M17.5 12v3.5");
}

:global(.wquo_ibsk) {
  d: path("M6.5 8.5V12");
}

:global(.z8ojisy5e) {
  fill: currentColor;
  d: path("M13 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
