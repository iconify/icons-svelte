<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l7yfq-b6e"/><circle class="bepmk1bhd"/><path class="h3qkj9bop"/><path class="lnxn6ebus"/><path class="rio5yf-5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:turntable-sharp" {...props}></Icon>
<style>
:global(.bepmk1bhd) {
  cx: 10px;
  cy: 12px;
  r: 5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.h3qkj9bop) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01");
}

:global(.l7yfq-b6e) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

:global(.lnxn6ebus) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 7v6.5L16 16");
}

:global(.rio5yf-5e) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 7h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
