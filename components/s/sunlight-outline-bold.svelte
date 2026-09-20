<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ddr0zpdgr"/><path class="uix68becb"/><path class="lkivjibuo"/><path class="q4rhaacat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunlight-outline-bold" {...props}></Icon>
<style>
:global(.ddr0zpdgr) {
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.lkivjibuo) {
  d: path("M12 13v7");
}

:global(.q4rhaacat) {
  d: path("m16 13 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uix68becb) {
  d: path("m8 13 -4 4");
}

</style>
