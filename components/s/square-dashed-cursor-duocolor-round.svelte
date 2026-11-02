<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u1cy98bkr"/><path class="sautgxbgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-cursor-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sautgxbgs) {
  d: path("M3 6a3 3 0 0 1 3-3m12 0a3 3 0 0 1 3 3M6 21a3 3 0 0 1-3-3m7-15h4M3 14v-4");
}

:global(.u1cy98bkr) {
  stroke-opacity: 0.4;
  d: path("m9 9l12 4l-4 1l2 2a1.414 1.414 0 0 1 0 2l-1 1a1.414 1.414 0 0 1-2 0l-2-2l-1 4z");
}

</style>
