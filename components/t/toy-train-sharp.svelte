<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g-48vhpdu"/><path class="ah8jctbmd"/><circle class="k6r3zgz2g"/><circle class="sotefpb_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toy-train-sharp" {...props}></Icon>
<style>
:global(.ah8jctbmd) {
  d: path("M15 7.5h3.25v3.75H15Z");
}

:global(.g-48vhpdu) {
  d: path("M2.75 13.25V9h2V4.5h3.5V9H12V4.5h9.25v9.75H2.75z");
}

:global(.k6r3zgz2g) {
  cx: 6.75px;
  cy: 19.25px;
  r: 2px;
}

:global(.sotefpb_j) {
  cx: 17px;
  cy: 19.25px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
