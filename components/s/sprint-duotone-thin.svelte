<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cgousu48d"/><path class="kwbe3flqa"/><path class="exbw4cc5o"/><path class="reszlpgvw"/><path class="pxcz33phn"/><path class="a-xc2ibwn"/><path class="u46xm9b9w"/><path class="g6v1wdg_x"/><path class="q1ae0k4gd"/><path class="z91-mkbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sprint-duotone-thin" {...props}></Icon>
<style>
:global(.a-xc2ibwn) {
  d: path("M12 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.cgousu48d) {
  fill: currentColor;
  d: path("M12 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.exbw4cc5o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12 6 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g6v1wdg_x) {
  d: path("M10 12 6 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kwbe3flqa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pxcz33phn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q1ae0k4gd) {
  d: path("m14 16 4 4");
}

:global(.reszlpgvw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 16 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u46xm9b9w) {
  d: path("m14 8 -4 4 4 4");
}

:global(.z91-mkbau) {
  d: path("M3 20h5");
}

</style>
