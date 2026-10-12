<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="o8w52mbli"/><circle class="t8ttqnb2f"/><path class="mlvjywbib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:webcam-sharp" {...props}></Icon>
<style>
:global(.mlvjywbib) {
  d: path("M12 16.75v4.5m-4.25 0h8.5");
}

:global(.o8w52mbli) {
  cx: 12px;
  cy: 9.75px;
  r: 7px;
}

:global(.t8ttqnb2f) {
  cx: 12px;
  cy: 9.75px;
  r: 3px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
