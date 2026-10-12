<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="gg525p0gt"/><path class="mqoc1vb-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:user-lightbulb" {...props}></Icon>
<style>
:global(.gg525p0gt) {
  cx: 12px;
  cy: 7.25px;
  r: 4px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mqoc1vb-o) {
  d: path("M5 20.25h14a1 1 0 0 0 1-1c0-3-3.6-5.25-8-5.25s-8 2.25-8 5.25a1 1 0 0 0 1 1");
}

</style>
