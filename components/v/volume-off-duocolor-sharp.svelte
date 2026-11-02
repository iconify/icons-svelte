<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axcf-wb4p"/><path class="vkrj_abij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.axcf-wb4p) {
  stroke-opacity: 0.4;
  d: path("m2 2l20 20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vkrj_abij) {
  d: path("M8 8H6v8h4l4 4v-6m0-6V4l-2 2");
}

</style>
