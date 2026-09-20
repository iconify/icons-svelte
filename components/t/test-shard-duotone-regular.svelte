<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b7kolodzb"/><path class="g_po6wbmj"/><path class="tfixfresq"/><path class="kt4jgwb2r"/><path class="j-70hcbzd"/><path class="j_72l_3ug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:test-shard-duotone-regular" {...props}></Icon>
<style>
:global(.b7kolodzb) {
  fill: currentColor;
  d: path("m3 8 4 4 -4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g_po6wbmj) {
  fill: currentColor;
  d: path("m10 8 4 4 -4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j_72l_3ug) {
  d: path("m17 8 4 4 -4 4Z");
}

:global(.j-70hcbzd) {
  d: path("m10 8 4 4 -4 4Z");
}

:global(.kt4jgwb2r) {
  d: path("m3 8 4 4 -4 4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tfixfresq) {
  fill: currentColor;
  d: path("m17 8 4 4 -4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
