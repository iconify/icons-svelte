<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z42lsfsjq"/><path class="l517yxbln"/><path class="uykaiekji"/><path class="awxqv1b4c"/><path class="jlc2f9rpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:water-plant-outline-regular" {...props}></Icon>
<style>
:global(.awxqv1b4c) {
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jlc2f9rpk) {
  d: path("M19 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uykaiekji) {
  d: path("M12 13c-3 0 -5 -2 -5 -5 3 0 5 2 5 5");
}

:global(.z42lsfsjq) {
  d: path("M8 15v6h8v-6Z");
}

</style>
