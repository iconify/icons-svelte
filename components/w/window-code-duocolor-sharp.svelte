<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qvhxydska"/><path class="vrlw9abfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-code-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvhxydska) {
  stroke-opacity: 0.4;
  d: path("m10 12l-2 2l2 2m4-4l2 2l-2 2");
}

:global(.vrlw9abfp) {
  d: path("M3 8V4h18v16H3zm0 0h18");
}

</style>
