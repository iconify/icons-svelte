<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yr-wyvb1u"/><path class="w5cma-9_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:submarine-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.w5cma-9_p) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 20H9a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h1V9a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3h3a4 4 0 1 1 0 8M3 12v8m0-4h4m5-8V6a2 2 0 0 1 2-2h2m-4 12h.01M16 16h.01");
}

:global(.yr-wyvb1u) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 18v-4a3 3 0 0 1 3-3V9a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2h2a5 5 0 0 1 0 10H9a3 3 0 0 1-3-3");
}

</style>
