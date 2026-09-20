<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mjxjq9e4f"/><path class="bzecsub_a"/><path class="y_or9-s0p"/><path class="oeboj9bgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:test-select-outline-regular" {...props}></Icon>
<style>
:global(.bzecsub_a) {
  d: path("M8 12h12");
}

:global(.mjxjq9e4f) {
  d: path("M8 5h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oeboj9bgs) {
  d: path("m3 9 3 3 -3 3Z");
}

:global(.y_or9-s0p) {
  d: path("M8 19h12");
}

</style>
