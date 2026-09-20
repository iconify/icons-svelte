<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t12-ippwj"/><path class="jcj1h_mmu"/><path class="wzdwamk1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:self-join-outline-regular" {...props}></Icon>
<style>
:global(.jcj1h_mmu) {
  d: path("M4.5 10.26a8 8 0 0 1 15.04 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t12-ippwj) {
  d: path("M7 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.wzdwamk1s) {
  d: path("M17 6h3v3");
}

</style>
