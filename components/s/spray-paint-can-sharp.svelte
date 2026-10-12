<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="yew390bse"/><path class="aaaonzuou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spray-paint-can-sharp" {...props}></Icon>
<style>
:global(.aaaonzuou) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 4.25h.01m2.99-1h.01m-1.01 3.5h.01m3.24-.5h.01M20 9.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.yew390bse) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 9.25h9v12h-9zm0 4.25h9M6 5.75h5.5v3.5H6zm1.25-3h3v3h-3z");
}

</style>
