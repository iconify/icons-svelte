<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j5c00cbyg"/><rect class="ltbxgjbdp"/><path class="v8gj1kz9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:soy-sauce" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j5c00cbyg) {
  d: path("M10 9h4c0 2.5 5 4.5 5 8.25A3.75 3.75 0 0 1 15.25 21h-6.5A3.75 3.75 0 0 1 5 17.25C5 13.5 10 11.5 10 9");
}

:global(.ltbxgjbdp) {
  width: 6px;
  height: 3px;
  x: 9px;
  y: 6px;
  rx: 0.75px;
}

:global(.v8gj1kz9u) {
  d: path("m15 7l3-2M5.52 15.2h12.96");
}

</style>
