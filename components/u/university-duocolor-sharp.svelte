<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qxb1eforw"/><path class="d-_53y6hj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:university-duocolor-sharp" {...props}></Icon>
<style>
:global(.d-_53y6hj) {
  d: path("m12 3l8 3l-8 3l-8-3zM3 21h18M20 6v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qxb1eforw) {
  stroke-opacity: 0.4;
  d: path("M6 12v5m4-5v5m4-5v5m4-5v5");
}

</style>
