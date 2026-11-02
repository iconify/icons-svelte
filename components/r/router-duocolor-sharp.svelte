<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jsdo7gbfr"/><path class="fw854spnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:router-duocolor-sharp" {...props}></Icon>
<style>
:global(.fw854spnl) {
  d: path("M3 15h18v6H3Zm4 3h.01M11 18h.01");
}

:global(.jsdo7gbfr) {
  stroke-opacity: 0.4;
  d: path("M16 12v3m-2-6a2.83 2.83 0 0 1 4 0m-7-3a7.07 7.07 0 0 1 10 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
