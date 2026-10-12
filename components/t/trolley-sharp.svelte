<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hogdls_gf"/><path class="plgbawb6y"/><circle class="j2ov4djsy"/><path class="tvc__j9qb"/><circle class="riohgnbtm"/><path class="g27ahybtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trolley-sharp" {...props}></Icon>
<style>
:global(.g27ahybtf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 19h.01");
}

:global(.hogdls_gf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h2l2.4 12H18.7");
}

:global(.j2ov4djsy) {
  cx: 10.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.plgbawb6y) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 7.75h8.5V14h-8.5zm2.25 0V5.5h4v2.25");
}

:global(.riohgnbtm) {
  cx: 17.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tvc__j9qb) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 19h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
