<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ckdeowbwc"/><path class="peh8vw5vo"/><path class="dsd-7lbgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shrug" {...props}></Icon>
<style>
:global(.ckdeowbwc) {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
}

:global(.dsd-7lbgn) {
  d: path("M6.75 16L4 17l-1-2.5M17.25 16L20 17l1-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.peh8vw5vo) {
  d: path("M7.5 21.25a1 1 0 0 1-1-1v-2.5a5.5 5.5 0 0 1 11 0v2.5a1 1 0 0 1-1 1Z");
}

</style>
