<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xq1pi7btv"/><path class="qi3wr9i3q"/><path class="q686vz2zk"/><path class="zky22zblb"/><path class="j4nym3cre"/><path class="m1z_l4h_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:traceroute-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4nym3cre) {
  d: path("m6 16 2 -2");
}

:global(.m1z_l4h_u) {
  d: path("m12 11 2 -2");
}

:global(.q686vz2zk) {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qi3wr9i3q) {
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xq1pi7btv) {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zky22zblb) {
  d: path("M20 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
