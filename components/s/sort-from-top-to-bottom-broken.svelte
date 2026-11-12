<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u9u89mb-h"/><path class="n-8nhbbnb"/><path class="yoy8e1bnl"/><path class="h82hcmbpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-from-top-to-bottom-broken" {...props}></Icon>
<style>
:global(.h82hcmbpo) {
  stroke-linejoin: round;
  d: path("M17 4V20L20 16");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n-8nhbbnb) {
  d: path("M6 11H13");
}

:global(.u9u89mb-h) {
  d: path("M4 16L13 16");
}

:global(.yoy8e1bnl) {
  d: path("M8 6L13 6");
}

</style>
