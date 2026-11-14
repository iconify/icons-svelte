<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="exq_iqwok"/><path class="i7i8upspy"/><path class="naxwb80nf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:water-footprint" {...props}></Icon>
<style>
:global(.exq_iqwok) {
  d: path("M12 6c2.5 3 4 5 4 7.5a4 4 0 0 1-8 0C8 11 9.5 9 12 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7i8upspy) {
  d: path("M6.215 5.106a9 9 0 1 1-2.672 9.972");
}

:global(.naxwb80nf) {
  d: path("M6.25 2.25L9 3.5L7.75 6.25");
}

</style>
