<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rb-l41-ka"/><path class="jrvuve-_c"/><path class="x1f4lc3zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:separator-vertical-linear" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jrvuve-_c) {
  d: path("M15 18L21 12L15 6");
}

:global(.rb-l41-ka) {
  d: path("M9 18L3 12L9 6");
}

:global(.x1f4lc3zb) {
  d: path("M12 2L12 22");
}

</style>
