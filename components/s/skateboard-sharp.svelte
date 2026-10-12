<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bjd3m4byv"/><circle class="v0gbo5fpj"/><circle class="rslbrvbax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:skateboard-sharp" {...props}></Icon>
<style>
:global(.bjd3m4byv) {
  d: path("M2.75 10.5V9h2.5l1.5 1.25h10.5L18.75 9h2.5v1.5c0 1.75-1.5 3.25-3.25 3.25H2.75z");
}

:global(.rslbrvbax) {
  cx: 17px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.v0gbo5fpj) {
  cx: 7px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
