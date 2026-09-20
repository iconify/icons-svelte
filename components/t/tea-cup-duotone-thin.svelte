<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l3bfc0bau"/><path class="a5svpccsg"/><path class="xl83b8b9f"/><path class="s7yzvqbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tea-cup-duotone-thin" {...props}></Icon>
<style>
:global(.a5svpccsg) {
  d: path("M5 9v9h11V9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l3bfc0bau) {
  fill: currentColor;
  d: path("M8 2h5v3H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s7yzvqbuw) {
  d: path("M8 2h5v3H8Z");
}

:global(.xl83b8b9f) {
  d: path("M10 9V5");
}

</style>
