<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z7k3ah_pl"/><path class="g3h0tdpmx"/><path class="hepscxtpv"/><circle class="lqa0robbd"/><path class="bcvszibcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:screen-time-kids-sharp" {...props}></Icon>
<style>
:global(.bcvszibcg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 13.25V15L19 16");
}

:global(.g3h0tdpmx) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 9.5h.01M9 9.5h.01");
}

:global(.hepscxtpv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.75v2h4v-2");
}

:global(.lqa0robbd) {
  cx: 17.75px;
  cy: 15px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.z7k3ah_pl) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h9.5v18.5h-9.5z");
}

</style>
