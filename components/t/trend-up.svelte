<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r-07k_b6z"/><path class="hkg8_gt-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trend-up" {...props}></Icon>
<style>
:global(.hkg8_gt-w) {
  d: path("M15.5 7h5v5");
}

:global(.r-07k_b6z) {
  d: path("m3 18l5-5.5l4 3L20.5 7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
