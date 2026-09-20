<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rbwzp5g7d"/><path class="y0676ebxw"/><path class="y0c1235en"/><path class="gy18-zqeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shell-duotone-bold" {...props}></Icon>
<style>
:global(.gy18-zqeb) {
  d: path("M14 19h7");
}

:global(.rbwzp5g7d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y0676ebxw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 19h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y0c1235en) {
  d: path("m4 5 7 7 -7 7");
}

</style>
