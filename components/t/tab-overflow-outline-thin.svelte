<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="yegul17ht"/><path class="ec5tld62j"/><path class="gju7e2bvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-overflow-outline-thin" {...props}></Icon>
<style>
:global(.ec5tld62j) {
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gju7e2bvn) {
  d: path("M20 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oscmqi7_r) {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

:global(.yegul17ht) {
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
