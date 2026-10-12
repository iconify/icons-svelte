<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wjs2vuzum"/><circle class="f35nbaban"/><path class="nrfpa2b3d"/><circle class="ltvwwkb6z"/><path class="q-9rn4g0x"/><circle class="efb4smbdq"/><path class="z-k1rmdkw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:semi-truck-sharp" {...props}></Icon>
<style>
:global(.efb4smbdq) {
  cx: 18.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.f35nbaban) {
  cx: 5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ltvwwkb6z) {
  cx: 11.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nrfpa2b3d) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 19h.01");
}

:global(.q-9rn4g0x) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.75 19h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wjs2vuzum) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h10.5v11H2.75zm12.75 11v-8h2.85l.782.001l.188.759l.5 2.1l1.43.505v4.635Zm0-4.5h5.75");
}

:global(.z-k1rmdkw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 19h.01");
}

</style>
