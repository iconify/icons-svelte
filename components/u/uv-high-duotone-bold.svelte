<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gdy036bip"/><path class="e6h0tjbiq"/><path class="wiboc7buh"/><path class="f50fjsbgi"/><path class="o8od38cnm"/><path class="tjpylcvyr"/><path class="drjad9bfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:uv-high-duotone-bold" {...props}></Icon>
<style>
:global(.drjad9bfe) {
  d: path("M14 14v4");
}

:global(.e6h0tjbiq) {
  d: path("M8 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.f50fjsbgi) {
  d: path("M19.5 3.5 17 6");
}

:global(.gdy036bip) {
  fill: currentColor;
  d: path("M8 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tjpylcvyr) {
  d: path("M18 11v7");
}

:global(.wiboc7buh) {
  d: path("M4.5 3.5 7 6");
}

</style>
