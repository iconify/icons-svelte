<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jz9jnbbik"/><path class="phefmrbhr"/><path class="bbyt2gbhw"/><path class="ybyc8pxiv"/><path class="hii_9808s"/><path class="aeyekmbly"/><path class="axr3xwb0d"/><path class="cn1mb64lb"/><path class="r1wy_ibgj"/><path class="jhhozmbca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:strategy-duotone-bold" {...props}></Icon>
<style>
:global(.aeyekmbly) {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.axr3xwb0d) {
  d: path("m7 17 4 -4");
}

:global(.bbyt2gbhw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 13h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cn1mb64lb) {
  d: path("M11 13h4");
}

:global(.hii_9808s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 5v4h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jhhozmbca) {
  d: path("M19 5v4h-4");
}

:global(.jz9jnbbik) {
  fill: currentColor;
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.phefmrbhr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 17 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r1wy_ibgj) {
  d: path("m15 13 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ybyc8pxiv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 13 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
