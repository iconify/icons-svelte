<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w1o2eucmb"/><circle class="kd9qjyb-n"/><circle class="et5mm82sv"/><path class="c0jwhybud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scissors-salon-sharp" {...props}></Icon>
<style>
:global(.c0jwhybud) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.38h.01");
}

:global(.et5mm82sv) {
  cx: 16px;
  cy: 18px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kd9qjyb-n) {
  cx: 8px;
  cy: 18px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.w1o2eucmb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 2.75l6.84 13.04M16 2.75L9.16 15.79");
}

</style>
