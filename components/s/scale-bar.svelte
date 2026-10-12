<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hcpzo1bdd"/><path class="iudiszbon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scale-bar" {...props}></Icon>
<style>
:global(.hcpzo1bdd) {
  width: 18.5px;
  height: 4.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iudiszbon) {
  d: path("M8.92 9.75h6.17v4.5H8.92zM3.5 17.5V20m8.5-2.5V20m8.5-2.5V20");
}

</style>
