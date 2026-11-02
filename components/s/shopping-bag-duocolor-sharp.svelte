<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ooyw8-y8g"/><path class="i7bdhbb4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-bag-duocolor-sharp" {...props}></Icon>
<style>
:global(.i7bdhbb4s) {
  d: path("M5 6h14v15H5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ooyw8-y8g) {
  stroke-opacity: 0.4;
  d: path("M9 6a3 3 0 0 1 6 0");
}

</style>
