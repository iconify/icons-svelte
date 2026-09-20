<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u6_b2ld-z"/><path class="g91uwsb-i"/><path class="av-slcbjo"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tsunami-duotone-bold" {...props}></Icon>
<style>
:global(.av-slcbjo) {
  d: path("M2 17a10 10 0 0 1 18 -6 5 5 0 0 0 -8 0");
}

:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.g91uwsb-i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u6_b2ld-z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 17a10 10 0 0 1 18 -6 5 5 0 0 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
