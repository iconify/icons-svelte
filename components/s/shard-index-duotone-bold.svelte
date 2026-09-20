<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m_pa0sbgw"/><path class="fitbtb0gb"/><path class="es4r-tbix"/><path class="em5jngqaj"/><path class="q3ug_tb3n"/><path class="wthryk-vz"/><path class="b7nacdcee"/><path class="f8c172gmh"/><path class="qnmmmsbha"/><path class="zhf4ld96p"/><path class="tk_gkbbsy"/><path class="czv374byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shard-index-duotone-bold" {...props}></Icon>
<style>
:global(.b7nacdcee) {
  d: path("M3 6h6");
}

:global(.czv374byt) {
  d: path("M10 16h11");
}

:global(.em5jngqaj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.es4r-tbix) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f8c172gmh) {
  d: path("M12 6h9");
}

:global(.fitbtb0gb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m_pa0sbgw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q3ug_tb3n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tk_gkbbsy) {
  d: path("M3 16h4");
}

:global(.wthryk-vz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zhf4ld96p) {
  d: path("M17 11h4");
}

</style>
