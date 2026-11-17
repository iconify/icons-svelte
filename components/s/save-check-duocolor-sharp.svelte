<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qgo3vobus"/><path class="q38rixd8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:save-check-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q38rixd8d) {
  d: path("M3 3h14l4 4v14H3zm4 18v-7h10v7");
}

:global(.qgo3vobus) {
  stroke-opacity: 0.4;
  d: path("m9 9l2 2l4-4");
}

</style>
