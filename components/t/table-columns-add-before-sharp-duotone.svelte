<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jbp-1m4ig"/><path class="hruxdcckb"/><path class="jxmxjmbes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-columns-add-before-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hruxdcckb) {
  fill: currentColor;
  d: path("M12 22L12 2L22 2C22.5523 2 23 2.4477 23 3L23 21C23 21.5523 22.5523 22 22 22L12 22Z");
  stroke: none;
}

:global(.jbp-1m4ig) {
  stroke-opacity: 0.4;
  d: path("M4 18L4 21L13 21M13 3L4 3L4 6");
}

:global(.jxmxjmbes) {
  d: path("M5 8L5 16M1 12L9 12");
}

</style>
