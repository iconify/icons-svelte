<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="umy-09bor"/><path class="he9e6-b4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smart-display" {...props}></Icon>
<style>
:global(.he9e6-b4j) {
  d: path("M6.25 5.25h11.5v10H6.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.umy-09bor) {
  d: path("M3.5 2.5h17V18h-17ZM12 18v3.5m-3.5 0h7");
}

</style>
