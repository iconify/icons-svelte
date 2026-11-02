<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ahy_qimtf"/><path class="gjvdc8b5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:suspension-railway-duocolor-sharp" {...props}></Icon>
<style>
:global(.ahy_qimtf) {
  stroke-opacity: 0.4;
  d: path("M3 4h18M7 4v5m8-5v5");
}

:global(.gjvdc8b5x) {
  d: path("M3 20V9h14l4 4v7zm0-4h18M11 9v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
