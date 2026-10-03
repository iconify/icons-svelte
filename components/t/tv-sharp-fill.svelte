<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jnqct784c"/><path class="a0ynqh_ew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tv-sharp-fill" {...props}></Icon>
<style>
:global(.a0ynqh_ew) {
  d: path("M7.6998 2.6247L12 8L16.3002 2.6247");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.jnqct784c) {
  fill: currentColor;
  d: path("M2 7L22 7C22.5523 7 23 7.4477 23 8L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21L1 8C1 7.4477 1.4477 7 2 7Z");
  stroke: none;
}

</style>
