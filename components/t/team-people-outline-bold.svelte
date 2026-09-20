<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g_eatebwd"/><path class="kx8w1xsla"/><path class="hf-3i5bym"/><path class="jnbv45bnp"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:team-people-outline-bold" {...props}></Icon>
<style>
:global(.g_eatebwd) {
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hf-3i5bym) {
  d: path("M15 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jnbv45bnp) {
  d: path("M14 14a3 3 0 0 1 6 0");
}

:global(.kx8w1xsla) {
  d: path("M4 14a3 3 0 0 1 6 0");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
