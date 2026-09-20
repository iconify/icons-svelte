<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jzeve79sx"/><path class="i6w1_yb_p"/><path class="dzeqp9zwd"/><path class="xjtllvb6j"/><path class="yhxg0gb1u"/><path class="ifnz35boy"/><path class="wp14ejvwu"/><path class="ymw3aibdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trampoline-duotone-thin" {...props}></Icon>
<style>
:global(.dzeqp9zwd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6w1_yb_p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11c4 3 14 3 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ifnz35boy) {
  d: path("M5 12v8");
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wp14ejvwu) {
  d: path("M19 12v8");
}

:global(.xjtllvb6j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yhxg0gb1u) {
  d: path("M3 11c4 3 14 3 18 0");
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
