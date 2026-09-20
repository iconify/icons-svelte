<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b-_pqoidx"/><path class="fj_yfcb-v"/><path class="b1osgvbqx"/><path class="eyvjmxk-i"/><path class="ulh849bsj"/><path class="qh6hkcycj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:test-e2e-duotone-bold" {...props}></Icon>
<style>
:global(.b-_pqoidx) {
  fill: currentColor;
  d: path("M2 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.b1osgvbqx) {
  d: path("M2 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.eyvjmxk-i) {
  d: path("M9 10h4");
}

:global(.fj_yfcb-v) {
  fill: currentColor;
  d: path("M13 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qh6hkcycj) {
  d: path("m15 16 2 2 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ulh849bsj) {
  d: path("M13 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
