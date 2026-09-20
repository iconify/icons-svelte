<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rur1xzz4b"/><path class="rq-fg0mio"/><path class="em3t3yypy"/><path class="s2otp9flj"/><path class="p3ntj0cbi"/><path class="mqnae981n"/><path class="kwq9r2piz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:write-ahead-log-duotone-bold" {...props}></Icon>
<style>
:global(.em3t3yypy) {
  d: path("M2 5a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

:global(.kwq9r2piz) {
  d: path("M2 17a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.mqnae981n) {
  d: path("m9 11 3 3 3 -3");
}

:global(.p3ntj0cbi) {
  d: path("M15 2v6");
}

:global(.rq-fg0mio) {
  fill: currentColor;
  d: path("M2 17a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rur1xzz4b) {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
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

:global(.s2otp9flj) {
  d: path("M9 2v6");
}

</style>
