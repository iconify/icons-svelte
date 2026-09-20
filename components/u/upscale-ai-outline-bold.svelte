<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="viv5gg8xx"/><path class="jy7vpnbza"/><path class="neof5acyb"/><path class="ld04s_b-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:upscale-ai-outline-bold" {...props}></Icon>
<style>
:global(.jy7vpnbza) {
  d: path("M5 14.5a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2V17a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.ld04s_b-u) {
  d: path("M14.5 6H18v3.5");
}

:global(.neof5acyb) {
  d: path("m14 10 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.viv5gg8xx) {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
