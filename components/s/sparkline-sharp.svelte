<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bicgcfb5m"/><path class="cuhmvlbkj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sparkline-sharp" {...props}></Icon>
<style>
:global(.bicgcfb5m) {
  d: path("M2.75 5.75h18.5v12.5H2.75z");
}

:global(.cuhmvlbkj) {
  d: path("m6.25 13.75l2.5-2.5l2.5 2l3-4.5l3.5 3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
