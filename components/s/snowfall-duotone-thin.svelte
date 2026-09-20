<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-otzgx8d"/><path class="zhm4otbmz"/><path class="a1e57xbge"/><path class="uof3uv2_w"/><path class="uadcs425n"/><path class="uih_zvhtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:snowfall-duotone-thin" {...props}></Icon>
<style>
:global(.a1e57xbge) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m-otzgx8d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 3.5v7m-3.5 0 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uadcs425n) {
  d: path("M16 10.5v7m-3.5 0 7 -7");
}

:global(.uih_zvhtv) {
  d: path("M4 21h16");
}

:global(.uof3uv2_w) {
  d: path("M8 3.5v7m-3.5 0 7 -7");
}

:global(.zhm4otbmz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 10.5v7m-3.5 0 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
