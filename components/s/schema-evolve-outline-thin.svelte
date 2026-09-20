<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jy3t2qbob"/><path class="zyggqel0w"/><path class="slgjv5l0u"/><path class="rcu4irbnl"/><path class="p8a31xr4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:schema-evolve-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jy3t2qbob) {
  d: path("M3 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.p8a31xr4o) {
  d: path("M16 12h6");
}

:global(.rcu4irbnl) {
  d: path("M19 9v6");
}

:global(.slgjv5l0u) {
  d: path("M3 13h10");
}

:global(.zyggqel0w) {
  d: path("M3 8h10");
}

</style>
