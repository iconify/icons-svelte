<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="skxyjccos"/><path class="s-207ebhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:upload-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s-207ebhv) {
  d: path("m16 8l-4-4l-4 4m4-4v12");
}

:global(.skxyjccos) {
  stroke-opacity: 0.4;
  d: path("M4 16a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4");
}

</style>
