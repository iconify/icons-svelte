<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlnog1bgn"/><path class="w6fvlpypf"/><path class="vd0jm7r_j"/><path class="zslxt_5nz"/><path class="gvj63pubw"/><path class="ggzo1fbjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stream-job-outline-regular" {...props}></Icon>
<style>
:global(.ggzo1fbjx) {
  d: path("M6 20h6");
}

:global(.gvj63pubw) {
  d: path("M18 16h3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qlnog1bgn) {
  d: path("M6 6a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.vd0jm7r_j) {
  d: path("M3 16h6");
}

:global(.w6fvlpypf) {
  d: path("m9.5 6.5 2 2 -2 2");
}

:global(.zslxt_5nz) {
  d: path("M12 16h3");
}

</style>
