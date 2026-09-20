<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h4gumgb9f"/><path class="acyg6nb1v"/><path class="ikiprn9sq"/><path class="jlojnsdlu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:video-doorbell-outline-bold" {...props}></Icon>
<style>
:global(.acyg6nb1v) {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h4gumgb9f) {
  d: path("M7 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jlojnsdlu) {
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
