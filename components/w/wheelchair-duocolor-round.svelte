<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="et8vz1all"/><path class="p2ubz38vz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wheelchair-duocolor-round" {...props}></Icon>
<style>
:global(.et8vz1all) {
  stroke-opacity: 0.4;
  d: path("M9 11a5 5 0 1 0 4 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p2ubz38vz) {
  d: path("M8 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 4v4a2 2 0 0 0 2 2h3c.613 0 1.387.774 2 2l1 2c.613 1.226 1.387 2 2 2h1M9 10h5");
}

</style>
