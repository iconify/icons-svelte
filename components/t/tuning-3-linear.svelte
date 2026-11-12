<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><circle class="imrhgbc8c"/><circle class="qbe_3qbje"/><path class="ppfhar_-b"/><path class="h3if4--oh"/><path class="y59k8g5qg"/><path class="ofyiqqnwj"/><path class="xddt81bly"/><path class="t-rhypbnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tuning-3-linear" {...props}></Icon>
<style>
:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.h3if4--oh) {
  d: path("M20 10L20 5");
}

:global(.imrhgbc8c) {
  cx: 20px;
  cy: 14px;
  r: 2px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ofyiqqnwj) {
  d: path("M12 19L12 16");
}

:global(.ppfhar_-b) {
  d: path("M12 8L12 5");
}

:global(.qbe_3qbje) {
  cx: 4px;
  cy: 10px;
  r: 2px;
}

:global(.t-rhypbnu) {
  d: path("M4 5L4 6");
}

:global(.xddt81bly) {
  d: path("M20 19L20 18");
}

:global(.y59k8g5qg) {
  d: path("M4 14L4 19");
}

</style>
