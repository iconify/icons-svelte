<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k-sgg11ok"/><path class="bwxeoibzi"/><path class="jtt8g10_o"/><path class="ikiprn9sq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:websocket-outline-regular" {...props}></Icon>
<style>
:global(.bwxeoibzi) {
  d: path("M15 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jtt8g10_o) {
  d: path("M9 10h6");
}

:global(.k-sgg11ok) {
  d: path("M2 8a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
