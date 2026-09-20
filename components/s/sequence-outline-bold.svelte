<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dfcdzc65k"/><path class="orctd05jx"/><path class="bo51iypxr"/><path class="rija-f-oa"/><path class="kdmnrabtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sequence-outline-bold" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dfcdzc65k) {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kdmnrabtq) {
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.orctd05jx) {
  d: path("m7.5 7.5 2 2");
}

:global(.rija-f-oa) {
  d: path("m14.5 14.5 2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
