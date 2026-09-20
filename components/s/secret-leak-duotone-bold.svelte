<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="daotx-b_a"/><path class="pj1fh1brs"/><path class="vlhjfdbfm"/><path class="g8vjt7b7p"/><path class="b-fhdniix"/><path class="eoa7zubuy"/><path class="kut6h2oks"/><path class="mtc590bck"/><path class="ceatt7y_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:secret-leak-duotone-bold" {...props}></Icon>
<style>
:global(.b-fhdniix) {
  d: path("M2 9a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.ceatt7y_b) {
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.daotx-b_a) {
  fill: currentColor;
  d: path("M2 9a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.eoa7zubuy) {
  d: path("M5 7a3 3 0 0 1 6 0");
}

:global(.g8vjt7b7p) {
  fill: currentColor;
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kut6h2oks) {
  d: path("M18 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mtc590bck) {
  d: path("M16 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pj1fh1brs) {
  fill: currentColor;
  d: path("M18 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

:global(.vlhjfdbfm) {
  fill: currentColor;
  d: path("M16 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
