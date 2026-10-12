<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="wjlmhmb_i"/><path class="u7xi22b_k"/><path class="sz6e964qg"/><path class="hbdewjbtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:router-off" {...props}></Icon>
<style>
:global(.hbdewjbtf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 16.25h3");
}

:global(.sz6e964qg) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16.25h.01m3.49 0h.01");
}

:global(.u7xi22b_k) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3.25v9m10.5-9v9");
}

:global(.wjlmhmb_i) {
  width: 18.5px;
  height: 8px;
  x: 2.75px;
  y: 12.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
