<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wmp4kccwc"/><path class="w2dozdlxo"/><path class="jotk81b5q"/><path class="f4naz_w9a"/><path class="nl66y9men"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stash-duotone-thin" {...props}></Icon>
<style>
:global(.f4naz_w9a) {
  d: path("m9 5 3 3 3 -3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jotk81b5q) {
  d: path("M12 2v6");
}

:global(.nl66y9men) {
  d: path("M6 16h12");
}

:global(.w2dozdlxo) {
  d: path("M2 14a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.wmp4kccwc) {
  fill: currentColor;
  d: path("M2 14a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
