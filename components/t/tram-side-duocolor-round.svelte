<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c26ugccyd"/><path class="ga-pd4-4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tram-side-duocolor-round" {...props}></Icon>
<style>
:global(.c26ugccyd) {
  stroke-opacity: 0.4;
  d: path("M9 3h6m-3 0v4M3 21h18");
}

:global(.ga-pd4-4n) {
  d: path("M12 7h5a4 4 0 0 1 4 4v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2zm-9 5h18M8 7v5m5-5v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
