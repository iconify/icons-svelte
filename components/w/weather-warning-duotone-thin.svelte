<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l48yz708p"/><path class="w_mi5xczu"/><path class="uweslxo3x"/><path class="gwnaabclj"/><path class="ivqg9reic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:weather-warning-duotone-thin" {...props}></Icon>
<style>
:global(.gwnaabclj) {
  d: path("M12 9v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivqg9reic) {
  d: path("M11 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.l48yz708p) {
  fill: currentColor;
  d: path("M12 3.5 21.5 20h-19Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uweslxo3x) {
  d: path("M12 3.5 21.5 20h-19Z");
}

:global(.w_mi5xczu) {
  fill: currentColor;
  d: path("M11 17.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
