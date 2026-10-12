<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d4ss5kb_g"/><path class="a1tf33b2o"/><rect class="e0xoq0bah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trophy" {...props}></Icon>
<style>
:global(.a1tf33b2o) {
  d: path("M6.75 5.25h-1.5a2 2 0 0 0-2 2c0 2.25 1.75 3.75 4.25 4m9.75-6h1.5a2 2 0 0 1 2 2c0 2.25-1.75 3.75-4.25 4M12 14v4");
}

:global(.d4ss5kb_g) {
  d: path("M6.75 3.25h10.5v5.5a5.25 5.25 0 0 1-10.5 0Z");
}

:global(.e0xoq0bah) {
  width: 9.5px;
  height: 3.25px;
  x: 7.25px;
  y: 18px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
