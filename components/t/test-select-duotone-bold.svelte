<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="quua95b2b"/><path class="mjxjq9e4f"/><path class="bzecsub_a"/><path class="y_or9-s0p"/><path class="oeboj9bgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:test-select-duotone-bold" {...props}></Icon>
<style>
:global(.bzecsub_a) {
  d: path("M8 12h12");
}

:global(.mjxjq9e4f) {
  d: path("M8 5h12");
}

:global(.oeboj9bgs) {
  d: path("m3 9 3 3 -3 3Z");
}

:global(.quua95b2b) {
  fill: currentColor;
  d: path("m3 9 3 3 -3 3Z");
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

:global(.y_or9-s0p) {
  d: path("M8 19h12");
}

</style>
