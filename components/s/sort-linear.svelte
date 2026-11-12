<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e4mqvczqi"/><path class="rc9v4_v0w"/><path class="fml2qzxuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-linear" {...props}></Icon>
<style>
:global(.e4mqvczqi) {
  d: path("M22 7L2 7");
}

:global(.fml2qzxuh) {
  d: path("M16 17H8");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rc9v4_v0w) {
  d: path("M19 12L5 12");
}

</style>
