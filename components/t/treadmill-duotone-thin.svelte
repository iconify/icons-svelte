<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vffpa5rfz"/><path class="xr0buybxj"/><path class="h67al40ex"/><path class="wre--v3de"/><path class="ned58dbax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:treadmill-duotone-thin" {...props}></Icon>
<style>
:global(.h67al40ex) {
  d: path("M2 19h13v-4H2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ned58dbax) {
  d: path("M16 8h6V4h-6Z");
}

:global(.vffpa5rfz) {
  fill: currentColor;
  d: path("M2 19h13v-4H2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wre--v3de) {
  d: path("M15 17h4V8");
}

:global(.xr0buybxj) {
  fill: currentColor;
  d: path("M16 8h6V4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
