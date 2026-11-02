<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qkeh7ubxs"/><path class="jk-wm0uju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stamp-duocolor-sharp" {...props}></Icon>
<style>
:global(.jk-wm0uju) {
  d: path("M4 12h16v5H4Zm1 9h14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qkeh7ubxs) {
  stroke-opacity: 0.4;
  d: path("M10 12V8a2.828 2.828 0 1 1 4 0v4");
}

</style>
