<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rys98qb6q"/><path class="xa4_09bid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:swimming-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rys98qb6q) {
  stroke-opacity: 0.4;
  d: path("M17 8a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

:global(.xa4_09bid) {
  d: path("m5 11l5-3l4 3l-2 2m-9 4q3-3 6 0t6 0t6 0");
}

</style>
