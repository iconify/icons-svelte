<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="esxx8sbse"/><path class="z_brs82ek"/><path class="pzlahbz6p"/><path class="vujkqyb_z"/><path class="z3e--kb9y"/><path class="ts70t37mn"/><path class="swzjdoakn"/><path class="wuk2mlziz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:watch-var-duotone-thin" {...props}></Icon>
<style>
:global(.esxx8sbse) {
  fill: currentColor;
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.pzlahbz6p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 9 5 5h6l5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.swzjdoakn) {
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ts70t37mn) {
  d: path("m4 9 5 5h6l5 -5");
}

:global(.vujkqyb_z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

:global(.z_brs82ek) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 9 5 -5h6l5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z3e--kb9y) {
  d: path("m4 9 5 -5h6l5 5");
}

</style>
