<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h51gqww2n"/><path class="wquo_ibsk"/><path class="f8n4gobtp"/><path class="mc3x0bbgo"/><path class="w9rzo5b1c"/><path class="lgk47ib7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:time-difference-outline-bold" {...props}></Icon>
<style>
:global(.f8n4gobtp) {
  d: path("M6.5 12h3");
}

:global(.h51gqww2n) {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.lgk47ib7d) {
  d: path("M14.5 12h3");
}

:global(.mc3x0bbgo) {
  d: path("M13 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w9rzo5b1c) {
  d: path("M17.5 12v3.5");
}

:global(.wquo_ibsk) {
  d: path("M6.5 8.5V12");
}

</style>
