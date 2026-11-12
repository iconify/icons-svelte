<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><circle class="v90gbqbox"/><path class="eveg1sbcl"/><path class="ns0fhccwl"/><path class="s6le__b7v"/><path class="wf-yddc_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:socket-linear" {...props}></Icon>
<style>
:global(.eveg1sbcl) {
  d: path("M12 18.0001V16.5");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ns0fhccwl) {
  d: path("M12 7.5V6");
}

:global(.s6le__b7v) {
  stroke-linejoin: round;
  d: path("M10 12H10.0001");
}

:global(.v90gbqbox) {
  cx: 12px;
  cy: 12px;
  r: 6px;
}

:global(.wf-yddc_g) {
  stroke-linejoin: round;
  d: path("M14 12H14.0001");
}

:global(.xvjk-cbox) {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

</style>
