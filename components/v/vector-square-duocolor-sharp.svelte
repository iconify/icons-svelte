<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c60-qib9z"/><path class="f_tftibfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:vector-square-duocolor-sharp" {...props}></Icon>
<style>
:global(.c60-qib9z) {
  stroke-opacity: 0.4;
  d: path("M3 3h4v4H3Zm14 0h4v4h-4Zm0 14h4v4h-4ZM3 17h4v4H3Z");
}

:global(.f_tftibfv) {
  d: path("M7 5h10m2 2v10m-2 2H7m-2-2V7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
