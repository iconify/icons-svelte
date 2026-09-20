<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wgc1tobog"/><path class="arzd6yb6y"/><path class="j0skl1zmq"/><path class="hh50h1w7h"/><path class="qxhe48bjs"/><path class="c4x33d_yv"/><path class="j-ukqcc5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tulip-duotone-thin" {...props}></Icon>
<style>
:global(.arzd6yb6y) {
  fill: currentColor;
  d: path("M5 20c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.c4x33d_yv) {
  d: path("M5 20c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.hh50h1w7h) {
  d: path("M8 5v5l4 4 4 -4V5l-4 4Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j-ukqcc5l) {
  d: path("M13 20c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.j0skl1zmq) {
  fill: currentColor;
  d: path("M13 20c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qxhe48bjs) {
  d: path("M12 14v7");
}

:global(.wgc1tobog) {
  fill: currentColor;
  d: path("M8 5v5l4 4 4 -4V5l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
