<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jea8fibeb"/><path class="e3tmhtu7v"/><path class="gl2wyfu4j"/><path class="xsx-llilr"/><path class="ofphfjbqm"/><path class="a912fdbob"/><path class="xq1pi7btv"/><path class="qi3wr9i3q"/><path class="q686vz2zk"/><path class="zky22zblb"/><path class="j4nym3cre"/><path class="m1z_l4h_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:traceroute-duotone-bold" {...props}></Icon>
<style>
:global(.a912fdbob) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 11 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e3tmhtu7v) {
  fill: currentColor;
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gl2wyfu4j) {
  fill: currentColor;
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j4nym3cre) {
  d: path("m6 16 2 -2");
}

:global(.jea8fibeb) {
  fill: currentColor;
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m1z_l4h_u) {
  d: path("m12 11 2 -2");
}

:global(.ofphfjbqm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 16 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q686vz2zk) {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qi3wr9i3q) {
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xq1pi7btv) {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xsx-llilr) {
  fill: currentColor;
  d: path("M20 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zky22zblb) {
  d: path("M20 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
