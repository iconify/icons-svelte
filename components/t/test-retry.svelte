<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jks-j8nup"/><path class="zpb_sxbkz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:test-retry" {...props}></Icon>
<style>
:global(.jks-j8nup) {
  d: path("M20 12a8 8 0 1 1-2.25-5.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zpb_sxbkz) {
  d: path("M17.75 2.5v3.75H14");
}

</style>
