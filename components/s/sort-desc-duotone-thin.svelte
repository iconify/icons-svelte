<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7h8iyqlm"/><path class="di-mwobgn"/><path class="jv75tobai"/><path class="k4qo1xe9v"/><path class="xlekzhbnl"/><path class="vybq366mg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sort-desc-duotone-thin" {...props}></Icon>
<style>
:global(.b7h8iyqlm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.di-mwobgn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jv75tobai) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k4qo1xe9v) {
  d: path("M4 6h16");
}

:global(.vybq366mg) {
  d: path("M4 18h6");
}

:global(.xlekzhbnl) {
  d: path("M4 12h11");
}

</style>
