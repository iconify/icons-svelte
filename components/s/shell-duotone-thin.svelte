<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jqwpjgbhg"/><path class="ztw87lr4b"/><path class="y0c1235en"/><path class="gy18-zqeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shell-duotone-thin" {...props}></Icon>
<style>
:global(.gy18-zqeb) {
  d: path("M14 19h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jqwpjgbhg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y0c1235en) {
  d: path("m4 5 7 7 -7 7");
}

:global(.ztw87lr4b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 19h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
