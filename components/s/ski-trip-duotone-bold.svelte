<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hd0l8pb1q"/><path class="icz5z3nxr"/><path class="jsuatobfw"/><path class="tp3wfdbxm"/><path class="wt9iv5biz"/><path class="olx65-bog"/><path class="exyd3ub4k"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ski-trip-duotone-bold" {...props}></Icon>
<style>
:global(.exyd3ub4k) {
  d: path("m9 8 6 -6");
}

:global(.hd0l8pb1q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.icz5z3nxr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 8 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jsuatobfw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 8 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.olx65-bog) {
  d: path("m6 8 6 -6");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tp3wfdbxm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wt9iv5biz) {
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
}

</style>
