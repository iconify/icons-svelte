<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="etcad4b9c"/><path class="bgbshn1il"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-right-bulk-sharp" {...props}></Icon>
<style>
:global(.bgbshn1il) {
  d: path("M3 7h18a1 1 0 0 1 0 2h-5v11a1 1 0 0 1-2 0V9H3a1 1 0 0 1 0-2");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.etcad4b9c) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 4v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1");
}

</style>
