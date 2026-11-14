<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ys3f9inko"/><path class="l7w3msboc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:strip-mall" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l7w3msboc) {
  d: path("M5 21.5V16h2.5v5.5m1.75 0V16h2.5v5.5m1.75 0V16H16v5.5m1.75 0V16h2.5M5 12.5h14");
}

:global(.ys3f9inko) {
  d: path("M4 6h16a1.5 1.5 0 0 1 1.5 1.5V8A1.5 1.5 0 0 1 20 9.5H4A1.5 1.5 0 0 1 2.5 8v-.5A1.5 1.5 0 0 1 4 6m-.5 3.5v12h17v-12");
}

</style>
