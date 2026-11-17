<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dq5hx_b_u"/><path class="kt15klw-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:security-key-duotone-sharp" {...props}></Icon>
<style>
:global(.dq5hx_b_u) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7h12v10H3Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.kt15klw-y) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h12v10H3Zm6 4v2m12-1h-2m-4-3h6v6h-6");
}

</style>
