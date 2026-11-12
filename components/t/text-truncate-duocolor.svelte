<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tgbev8bfa"/><path class="p3zn41bdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-truncate-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3zn41bdm) {
  d: path("M3 6h18M3 18h6");
}

:global(.tgbev8bfa) {
  stroke-opacity: 0.4;
  d: path("M13 18h.01M17 18h.01M21 18h-.01");
}

</style>
