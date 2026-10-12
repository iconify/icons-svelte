<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><circle class="b5s2zlb_d"/><circle class="wdvn5vpwe"/><path class="tjp3z8b0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tax-return" {...props}></Icon>
<style>
:global(.b5s2zlb_d) {
  cx: 8.5px;
  cy: 7.5px;
  r: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tjp3z8b0t) {
  d: path("m15 7l-6 7.5M8.25 18h7.5");
}

:global(.wdvn5vpwe) {
  cx: 15.5px;
  cy: 14px;
  r: 1.5px;
}

:global(.x00qgzx7x) {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
