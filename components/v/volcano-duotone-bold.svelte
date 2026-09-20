<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pcb0p01se"/><path class="l4f5m0byt"/><path class="a8u3jfbrq"/><path class="cvahx_bgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:volcano-duotone-bold" {...props}></Icon>
<style>
:global(.a8u3jfbrq) {
  d: path("M10 13V9h4v4");
}

:global(.cvahx_bgf) {
  d: path("m9 9 3 -3 3 3");
}

:global(.l4f5m0byt) {
  d: path("m3 20 7 -7h4l7 7Z");
}

:global(.pcb0p01se) {
  fill: currentColor;
  d: path("m3 20 7 -7h4l7 7Z");
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

</style>
