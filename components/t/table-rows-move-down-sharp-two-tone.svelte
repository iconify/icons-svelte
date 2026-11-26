<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l3ydi4hqj"/><path class="p1zfmxbhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-rows-move-down-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.l3ydi4hqj) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L3 11L21 11L21 2Z");
  stroke: none;
}

:global(.p1zfmxbhx) {
  d: path("M6 20L3 20L3 2L21 2L21 20L18 20M3 11L21 11M12 15L12 22M8.7071 18.7071L12 22L15.2929 18.7071");
}

</style>
