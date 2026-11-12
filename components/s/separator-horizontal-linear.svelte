<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="duudpwbrb"/><path class="h0krthb9p"/><path class="xdk9_oksp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:separator-horizontal-linear" {...props}></Icon>
<style>
:global(.duudpwbrb) {
  d: path("M18 15L12 21L6 15");
}

:global(.h0krthb9p) {
  d: path("M18 9L12 3L6 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xdk9_oksp) {
  d: path("M2 12L22 12");
}

</style>
