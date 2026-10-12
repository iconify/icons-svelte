<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="noim-rbgv"/><circle class="f90gk5b2m"/><path class="et2_-pbzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:url-scan-sharp" {...props}></Icon>
<style>
:global(.et2_-pbzq) {
  d: path("m13.5 18.75l2.5 2.5");
}

:global(.f90gk5b2m) {
  cx: 11px;
  cy: 16.25px;
  r: 3.5px;
}

:global(.noim-rbgv) {
  d: path("M2.75 3.75h18.5v6H2.75zm4 4.5l1.5-3m1.25 3l1.5-3m1.75 1.5h5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
