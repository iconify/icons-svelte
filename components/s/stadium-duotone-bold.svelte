<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jer_tk4og"/><path class="r9vsub3-y"/><path class="tlag47v4y"/><path class="niggb1byh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stadium-duotone-bold" {...props}></Icon>
<style>
:global(.jer_tk4og) {
  fill: currentColor;
  d: path("M12 4c6 0 10 3 10 8s-4 8 -10 8 -10 -3 -10 -8 4 -8 10 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.niggb1byh) {
  d: path("M8 10h8v4H8Z");
}

:global(.r9vsub3-y) {
  fill: currentColor;
  d: path("M8 10h8v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tlag47v4y) {
  d: path("M12 4c6 0 10 3 10 8s-4 8 -10 8 -10 -3 -10 -8 4 -8 10 -8");
}

</style>
