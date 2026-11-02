<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sm1k5x4xf"/><path class="fxwoyf6jx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:superscript-duocolor-sharp" {...props}></Icon>
<style>
:global(.fxwoyf6jx) {
  d: path("m4 13l8 8m0-8l-8 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sm1k5x4xf) {
  stroke-opacity: 0.4;
  d: path("M16 5a2 2 0 1 1 4 0l-4 4h4");
}

</style>
