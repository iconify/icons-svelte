<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="abpx_yb0j"/><path class="k8br464fy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-rows-move-up-sharp-two-tone" {...props}></Icon>
<style>
:global(.abpx_yb0j) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13L3 22L21 22L21 13Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.k8br464fy) {
  d: path("M6 4L3 4L3 22L21 22L21 4L18 4M3 13L21 13M12 9L12 2M8.7071 5.2929L12 2L15.2929 5.2929");
}

</style>
