<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="g4_qklztr"/><circle class="orr73zjqz"/><path class="ba32btbbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:transfer-sharp" {...props}></Icon>
<style>
:global(.ba32btbbz) {
  d: path("M16.25 12h5M18.5 9.25L21.25 12l-2.75 2.75");
}

:global(.g4_qklztr) {
  cx: 8.5px;
  cy: 12px;
  r: 5.75px;
}

:global(.orr73zjqz) {
  cx: 8.5px;
  cy: 12px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
