<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qp45nix1v"/><circle class="qy61aob5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toggle-on-sharp" {...props}></Icon>
<style>
:global(.qp45nix1v) {
  d: path("M2.75 6.5h18.5v11H2.75z");
}

:global(.qy61aob5q) {
  cx: 15.75px;
  cy: 12px;
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
