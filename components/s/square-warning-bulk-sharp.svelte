<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpp7y5g_r"/><path class="j9q73968f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-warning-bulk-sharp" {...props}></Icon>
<style>
:global(.bpp7y5g_r) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.j9q73968f) {
  d: path("M13 8v5a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m-1 7h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
