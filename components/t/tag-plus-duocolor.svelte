<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkz22f2th"/><path class="cccw_tp0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tag-plus-duocolor" {...props}></Icon>
<style>
:global(.cccw_tp0q) {
  d: path("M19 14v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7l4-4h6l4 4zm-8-8h2");
}

:global(.mkz22f2th) {
  stroke-opacity: 0.4;
  d: path("M9 14h6m-3-3v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
