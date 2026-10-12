<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s0oiepv6v"/><circle class="e1_x4r67w"/><path class="keeb62bzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tic-tac-toe" {...props}></Icon>
<style>
:global(.e1_x4r67w) {
  cx: 4.75px;
  cy: 4.75px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.keeb62bzb) {
  d: path("m17.25 17.25l3 3m0-3l-3 3");
}

:global(.s0oiepv6v) {
  d: path("M9 3v18m6-18v18M3 9h18M3 15h18");
}

</style>
