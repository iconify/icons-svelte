<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ep1vzmbwa"/><path class="j675ko9wd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sand-dune" {...props}></Icon>
<style>
:global(.ep1vzmbwa) {
  d: path("M2.5 19C8 18 11 9 16 9c1.5 0 3.5 5 5.5 10Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j675ko9wd) {
  d: path("M10.5 16q2.5-1.75 5-.5M3.5 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
