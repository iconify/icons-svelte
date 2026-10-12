<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="alxzavb9e"/><circle class="em9cvctqt"/><path class="b4gzso3dl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:small-claims-sharp" {...props}></Icon>
<style>
:global(.alxzavb9e) {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 3.75h7.5m-7.5 2.75h5");
}

:global(.b4gzso3dl) {
  d: path("M12 13.5v3");
}

:global(.em9cvctqt) {
  cx: 12px;
  cy: 15px;
  r: 3.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
