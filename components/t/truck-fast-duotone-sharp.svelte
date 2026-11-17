<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w9fcs9j2r"/><path class="ftqtambtu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:truck-fast-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ftqtambtu) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18H3v-1M3 5h10v13m0-10h4l4 4v6h-2M9 18h6m-2-6h7M3 9h6m-6 4h4m-2 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.w9fcs9j2r) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 18V5h10v3h4l4 4v6h-2a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732H9a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732Z");
}

</style>
