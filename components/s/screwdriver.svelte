<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r_i9lbcsb"/><path class="u8enhobmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:screwdriver" {...props}></Icon>
<style>
:global(.r_i9lbcsb) {
  d: path("m3.161 15.889l5.303-5.303a1 1 0 0 1 1.415 0l3.535 3.535a1 1 0 0 1 0 1.415l-5.303 5.303a1 1 0 0 1-1.414 0l-3.536-3.536a1 1 0 0 1 0-1.414Z");
}

:global(.u8enhobmw) {
  d: path("m10.409 11.116l1.768-1.768l2.475 2.475l-1.768 1.768Zm3.005-.53l7.071-7.071M7.05 16.95l2.475-2.475");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
