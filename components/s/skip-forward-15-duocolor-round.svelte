<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ylk0v3brf"/><path class="t6s272bxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-forward-15-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t6s272bxs) {
  d: path("M4 8a8.944 8.944 0 0 1 16 0m-4 0h4V4");
}

:global(.ylk0v3brf) {
  stroke-opacity: 0.4;
  d: path("m6 15l2-2v8m10-8h-6v4h2c2 0 4 0 4 2s-2 2-4 2h-2");
}

</style>
