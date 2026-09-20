<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="llc-u9kbe"/><path class="yjzepunpt"/><path class="f_-gw6caf"/><path class="gh7xyhbdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:slow-query-outline-regular" {...props}></Icon>
<style>
:global(.f_-gw6caf) {
  d: path("M11 7v4");
}

:global(.gh7xyhbdv) {
  d: path("M11 11h3");
}

:global(.llc-u9kbe) {
  d: path("M5 11a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yjzepunpt) {
  d: path("M15.5 15.5 20 20");
}

</style>
