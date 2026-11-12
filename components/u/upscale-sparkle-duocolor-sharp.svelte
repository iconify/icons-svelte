<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n12xakjal"/><path class="mhl1upbax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:upscale-sparkle-duocolor-sharp" {...props}></Icon>
<style>
:global(.mhl1upbax) {
  d: path("M3 13h8v8H3Zm11-3l6-6m-4 0h4v4");
}

:global(.n12xakjal) {
  stroke-opacity: 0.4;
  d: path("M6 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
