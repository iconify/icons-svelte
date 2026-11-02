<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sfqdbdbqm"/><path class="pf6nnw99z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:smartwatch-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pf6nnw99z) {
  d: path("M6 8a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2Z");
}

:global(.sfqdbdbqm) {
  stroke-opacity: 0.4;
  d: path("M9 6V5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1M9 18v1a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-1");
}

</style>
