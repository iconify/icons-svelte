<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nr2mcrb0o"/><path class="wpfuevp-t"/><path class="q-8azacde"/><path class="i1jka66ox"/><path class="yd1dd2b-v"/><path class="hsnj9o-9y"/><path class="j4m0w2b-t"/><path class="p3dq04btg"/><path class="i9hpnuf0x"/><path class="z0ud8rb7a"/><path class="ys-dg812g"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unpivot-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i1jka66ox) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 10.5 12 13l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i9hpnuf0x) {
  d: path("M18 2v5.5");
}

:global(.j4m0w2b-t) {
  d: path("M6 2v5.5");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.nr2mcrb0o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p3dq04btg) {
  d: path("M12 2v5.5");
}

:global(.q-8azacde) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wpfuevp-t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yd1dd2b-v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

:global(.z0ud8rb7a) {
  d: path("M9.5 10.5 12 13l2.5 -2.5");
}

</style>
