<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fbde_z08y"/><path class="o1bec9b2h"/><path class="w3hyiobto"/><path class="vw_dl18nv"/><path class="da_3coiun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tag-alert-duotone-thin" {...props}></Icon>
<style>
:global(.da_3coiun) {
  d: path("M11 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.fbde_z08y) {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o1bec9b2h) {
  fill: currentColor;
  d: path("M11 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vw_dl18nv) {
  d: path("M12 10.5v3");
}

:global(.w3hyiobto) {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

</style>
