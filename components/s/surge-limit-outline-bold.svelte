<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rvwkn2b2s"/><path class="c4e1y7wvc"/><path class="bo51iypxr"/><path class="gyi-tobvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:surge-limit-outline-bold" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.c4e1y7wvc) {
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gyi-tobvb) {
  d: path("M20 5v14");
}

:global(.rvwkn2b2s) {
  d: path("M2 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
