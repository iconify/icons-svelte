<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c13n5ccfl"/><path class="bjzalvuax"/><path class="efnmt0b_s"/><path class="n09nomjwg"/><path class="ux6apgnet"/><path class="jagbzbbou"/><path class="c8tpvpbrt"/><path class="aabrznh9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:status-page-duotone-thin" {...props}></Icon>
<style>
:global(.aabrznh9u) {
  d: path("M10.5 14H14");
}

:global(.bjzalvuax) {
  fill: currentColor;
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.c13n5ccfl) {
  fill: currentColor;
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.c8tpvpbrt) {
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.efnmt0b_s) {
  fill: currentColor;
  d: path("M7 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jagbzbbou) {
  d: path("M10.5 10H17");
}

:global(.n09nomjwg) {
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

:global(.ux6apgnet) {
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
