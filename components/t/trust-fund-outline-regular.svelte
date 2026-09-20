<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g_k4bub3x"/><path class="guw4_4ovg"/><path class="so--shb1m"/><path class="judl2rxer"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trust-fund-outline-regular" {...props}></Icon>
<style>
:global(.g_k4bub3x) {
  d: path("M6 9h12v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3Z");
}

:global(.guw4_4ovg) {
  d: path("M8 9V4h8v5");
}

:global(.judl2rxer) {
  d: path("M10.5 15.5a1.5 1.5 0 0 1 3 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.so--shb1m) {
  d: path("M9 15.5h6v3H9Z");
}

</style>
