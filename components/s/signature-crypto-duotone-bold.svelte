<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q2rf3qbee"/><path class="k-gv_lb9q"/><path class="cmh_klbjb"/><path class="g9c4ykb9u"/><path class="h1h08f6go"/><path class="w69b-gima"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:signature-crypto-duotone-bold" {...props}></Icon>
<style>
:global(.cmh_klbjb) {
  d: path("m5 10 4 4");
}

:global(.g9c4ykb9u) {
  d: path("M11 12h10");
}

:global(.h1h08f6go) {
  d: path("M15 12v3");
}

:global(.k-gv_lb9q) {
  d: path("M3 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.q2rf3qbee) {
  fill: currentColor;
  d: path("M3 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
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

:global(.w69b-gima) {
  d: path("M19 12v4");
}

</style>
