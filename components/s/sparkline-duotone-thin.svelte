<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="flgom2bsr"/><path class="a942dbb5m"/><path class="x9oi04cha"/><path class="hhryeubon"/><path class="oi0elobpe"/><path class="wpfzotbdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sparkline-duotone-thin" {...props}></Icon>
<style>
:global(.a942dbb5m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 21h5v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.flgom2bsr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8V3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hhryeubon) {
  d: path("M3 8V3h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oi0elobpe) {
  d: path("M16 21h5v-5");
}

:global(.wpfzotbdn) {
  d: path("m5 16 4 -4 3 3 4 -4 3 3");
}

:global(.x9oi04cha) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 16 4 -4 3 3 4 -4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
