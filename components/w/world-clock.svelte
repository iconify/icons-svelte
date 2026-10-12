<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mdswc-b6o"/><path class="yj4rhqsqh"/><circle class="req4htxyv"/><path class="eseyp7btj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:world-clock" {...props}></Icon>
<style>
:global(.eseyp7btj) {
  d: path("M15.5 12.5v3l-2 1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mdswc-b6o) {
  cx: 9px;
  cy: 9px;
  r: 6.25px;
}

:global(.req4htxyv) {
  cx: 15.5px;
  cy: 15.5px;
  r: 5.75px;
}

:global(.yj4rhqsqh) {
  d: path("M9 5.5V9h2.5");
}

</style>
