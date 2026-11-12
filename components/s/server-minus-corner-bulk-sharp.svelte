<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kny-5kbex"/><path class="brg4fpbua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-minus-corner-bulk-sharp" {...props}></Icon>
<style>
:global(.brg4fpbua) {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM21 15a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2ZM7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kny-5kbex) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m0 10h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

</style>
