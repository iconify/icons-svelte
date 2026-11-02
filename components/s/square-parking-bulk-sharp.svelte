<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpp7y5g_r"/><path class="zcnxjr1kl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-parking-bulk-sharp" {...props}></Icon>
<style>
:global(.bpp7y5g_r) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.zcnxjr1kl) {
  d: path("M8 13V7a1 1 0 0 1 1-1h3a4 4 0 0 1 0 8h-2v3a1 1 0 0 1-2 0Zm2-1h2a1.999 1.999 0 0 0 1.732-3A2 2 0 0 0 12 8h-2Z");
}

</style>
