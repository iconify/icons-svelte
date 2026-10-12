<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s0oiepv6v"/><circle class="e1_x4r67w"/><path class="keeb62bzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tic-tac-toe-sharp" {...props}></Icon>
<style>
:global(.e1_x4r67w) {
  cx: 4.75px;
  cy: 4.75px;
  r: 2px;
}

:global(.keeb62bzb) {
  d: path("m17.25 17.25l3 3m0-3l-3 3");
}

:global(.s0oiepv6v) {
  d: path("M9 3v18m6-18v18M3 9h18M3 15h18");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
