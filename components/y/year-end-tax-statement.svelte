<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u18_l1bej"/><path class="v6_5zjb7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:year-end-tax-statement" {...props}></Icon>
<style>
:global(.u18_l1bej) {
  d: path("M5 2.5h14v19L17 20l-2 1.5l-2-1.5l-2 1.5L9 20l-2 1.5L5 20Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v6_5zjb7p) {
  d: path("M8 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-4 .5l6-7");
}

</style>
