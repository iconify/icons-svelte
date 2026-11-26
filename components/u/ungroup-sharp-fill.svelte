<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ucxk7b0pm"/><path clip-rule="evenodd" class="ybrha9boy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ungroup-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ucxk7b0pm) {
  d: path("M9 12L3 12L3 21L12 21L12 15M8 2L8 5.5M2 8L5.5 8M16 18.5L16 22M18.5 16L22 16");
}

:global(.ybrha9boy) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 2L21 2C21.5523 2 22 2.4477 22 3L22 12C22 12.5523 21.5523 13 21 13L12 13C11.4477 13 11 12.5523 11 12L11 3C11 2.4477 11.4477 2 12 2Z");
  stroke: none;
}

</style>
