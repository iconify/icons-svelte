<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m_nn46xea"/><path class="zebfqmb5m"/><path class="dcw09dptt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:zoning-permit" {...props}></Icon>
<style>
:global(.dcw09dptt) {
  fill: currentColor;
  d: path("M14.5 14.5H18V18h-3.5ZM18 18h3.5v3.5H18Z");
}

:global(.m_nn46xea) {
  d: path("M11.7 21.5H4.5v-19h15v9.2M8 7h8m-8 3.5h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zebfqmb5m) {
  d: path("M14.5 14.5h7v7h-7Zm3.5 0v7M14.5 18h7");
}

</style>
