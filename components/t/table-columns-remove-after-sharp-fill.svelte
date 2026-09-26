<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yom8s_gar"/><path class="tc1x7zbgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-columns-remove-after-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tc1x7zbgv) {
  d: path("M20 6L20 3L2 3L2 21L20 21L20 18M11 3L11 21M15.7071 8.7071L22.2929 15.2929M22.2929 8.7071L15.7071 15.2929");
}

:global(.yom8s_gar) {
  fill: currentColor;
  d: path("M11 3L11 21L2 21L2 3L11 3Z");
  stroke: none;
}

</style>
