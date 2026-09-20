<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yo2xhpbcn"/><path class="rdjfllbip"/><path class="k85h_vh6j"/><path class="axz8bmb1c"/><path class="h69dzcbeh"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sea-port-outline-thin" {...props}></Icon>
<style>
:global(.axz8bmb1c) {
  d: path("M17 4v6");
}

:global(.h69dzcbeh) {
  d: path("M14 10h6v4h-6Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k85h_vh6j) {
  d: path("m5 9 5 -5");
}

:global(.rdjfllbip) {
  d: path("M5 4h14");
}

:global(.yo2xhpbcn) {
  d: path("M5 4v15");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
