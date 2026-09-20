<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x7f8f6eaf"/><path class="stzpsrbzr"/><path class="hx0a2p59k"/><path class="krlm5__2s"/><path class="cnveleblr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:toaster-duotone-bold" {...props}></Icon>
<style>
:global(.cnveleblr) {
  d: path("M2 11v6");
}

:global(.hx0a2p59k) {
  d: path("M8 11h4");
}

:global(.krlm5__2s) {
  d: path("M14 11h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.stzpsrbzr) {
  d: path("M5 10a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.x7f8f6eaf) {
  fill: currentColor;
  d: path("M5 10a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
