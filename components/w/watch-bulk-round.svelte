<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vkd5_obwx"/><path class="dtv6y-blv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:watch-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dtv6y-blv) {
  d: path("M8 6a4 4 0 0 1 8 0v2a1 1 0 0 1-2 0V6a2 2 0 1 0-4 0v2a1 1 0 0 1-2 0Zm5 4v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0m-3 8a2 2 0 1 0 4 0v-2a1 1 0 0 1 2 0v2a4 4 0 0 1-8 0v-2a1 1 0 0 1 2 0Z");
}

:global(.vkd5_obwx) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 12a6 6 0 1 1 12 0a6 6 0 0 1-12 0");
}

</style>
