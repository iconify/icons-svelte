<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="yf_brbf0s"/><path class="t9_u0sbsd"/><path class="zt91q8buo"/><path class="pz7pt3bwd"/><path class="h4c0sdbin"/><path class="xgrfb-bqu"/><path class="d8abqfbpc"/><path class="k0js09kko"/><path class="qouhnhnfp"/><path class="t40-rxb9c"/><path class="elwkggrsn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-complete-duotone-thin" {...props}></Icon>
<style>
:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.elwkggrsn) {
  d: path("M22 13.5v5");
}

:global(.h4c0sdbin) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M22 13.5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k0js09kko) {
  d: path("M3 16h9");
}

:global(.pz7pt3bwd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 13.5 19 16l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qouhnhnfp) {
  d: path("M15 16h4");
}

:global(.t40-rxb9c) {
  d: path("M16.5 13.5 19 16l-2.5 2.5");
}

:global(.t9_u0sbsd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.yf_brbf0s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zt91q8buo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
