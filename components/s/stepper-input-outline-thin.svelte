<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oh4p-ccfe"/><path class="qaaxrs2gg"/><path class="wrfjs43gu"/><path class="fxkurobsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stepper-input-outline-thin" {...props}></Icon>
<style>
:global(.fxkurobsu) {
  d: path("M17.5 10.5v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oh4p-ccfe) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.qaaxrs2gg) {
  d: path("M5 12h3");
}

:global(.wrfjs43gu) {
  d: path("M16 12h3");
}

</style>
