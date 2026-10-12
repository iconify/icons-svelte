<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pi3kb7blf"/><circle class="lb_5ccc9w"/><path class="nvy7_1wcy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:savings-sharp" {...props}></Icon>
<style>
:global(.lb_5ccc9w) {
  cx: 12px;
  cy: 7.5px;
  r: 4px;
}

:global(.nvy7_1wcy) {
  d: path("m13.13 6.52l-.35-.75h-1.94v.86c0 1.22 2.34.61 2.34 1.78v.83h-2.018l-.292-.73");
}

:global(.pi3kb7blf) {
  d: path("M3.75 11.5h16.5v9.75H3.75zm5 4.75h6.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
