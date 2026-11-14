<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_l24xs1z"/><path class="gf1mprotf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:walkthrough-detector" {...props}></Icon>
<style>
:global(.gf1mprotf) {
  d: path("M8 12.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p_l24xs1z) {
  d: path("M5 21.5V3h14v18.5");
}

</style>
