<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="myhtxf7hg"/><path class="ctyf6kbiv"/><path class="h7cexsulr"/><path class="pdx7buv0t"/><path class="m_-1pbc9n"/><path class="srcd877rx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:temperature-check-duotone-thin" {...props}></Icon>
<style>
:global(.ctyf6kbiv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M22 3h-4v5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7cexsulr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 5.5h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_-1pbc9n) {
  d: path("M22 3h-4v5h4");
}

:global(.myhtxf7hg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21v-4c-2 -2 -3 -5 -3 -8a7 7 0 0 1 14 -1c0 2 2 3 2 4s-1 1 -2 1v3a2 2 0 0 1 -2 2h-3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pdx7buv0t) {
  d: path("M6 21v-4c-2 -2 -3 -5 -3 -8a7 7 0 0 1 14 -1c0 2 2 3 2 4s-1 1 -2 1v3a2 2 0 0 1 -2 2h-3v3");
}

:global(.srcd877rx) {
  d: path("M18 5.5h-3");
}

</style>
