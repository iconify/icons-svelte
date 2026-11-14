<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrl3z9ene"/><path class="zqk0r_g7t"/><path class="zr9bgyb0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stablecoin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zqk0r_g7t) {
  d: path("M2.5 9v3a4 2.5 0 0 0 8 0V9m3 0a4 2.5 0 1 0 8 0a4 2.5 0 1 0-8 0");
}

:global(.zr9bgyb0d) {
  d: path("M13.5 9v3a4 2.5 0 0 0 8 0V9m-19 8.5h19");
}

:global(.zrl3z9ene) {
  d: path("M2.5 9a4 2.5 0 1 0 8 0a4 2.5 0 1 0-8 0");
}

</style>
