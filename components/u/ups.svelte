<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qvosu0b2k"/><path class="h1_jqsb7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ups" {...props}></Icon>
<style>
:global(.h1_jqsb7i) {
  d: path("M8.5 5.75h7M13 9.5l-3 4.25h4L11 18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qvosu0b2k) {
  width: 14px;
  height: 18.5px;
  x: 5px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
