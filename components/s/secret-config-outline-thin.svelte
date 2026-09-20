<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abnm6smsv"/><path class="dxebngfxk"/><path class="a97qfmbix"/><path class="tb5ui_brh"/><path class="yegul17ht"/><path class="dk412jbfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:secret-config-outline-thin" {...props}></Icon>
<style>
:global(.a97qfmbix) {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.dk412jbfb) {
  d: path("M8 17h4");
}

:global(.dxebngfxk) {
  d: path("M8 9h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tb5ui_brh) {
  d: path("M8 13h4");
}

:global(.yegul17ht) {
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
