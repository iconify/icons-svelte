<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kr5if0b2e"/><path class="mmnpqegwb"/><path class="ppbx_abyw"/><path class="tvr_k_bbt"/><path class="n8wwq96fg"/><path class="my0fs8b6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:session-duotone-bold" {...props}></Icon>
<style>
:global(.kr5if0b2e) {
  fill: currentColor;
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mmnpqegwb) {
  fill: currentColor;
  d: path("M14 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.my0fs8b6j) {
  d: path("m19 17 3 3");
}

:global(.n8wwq96fg) {
  d: path("M14 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.ppbx_abyw) {
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tvr_k_bbt) {
  d: path("M4 19a5 5 0 0 1 10 0");
}

</style>
