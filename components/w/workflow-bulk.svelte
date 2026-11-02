<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sfso60bve"/><path class="i28zdqj7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:workflow-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.i28zdqj7q) {
  d: path("M9 16h4a1 1 0 0 1 0 2H9a3.004 3.004 0 0 1-3-3v-4a1 1 0 0 1 2 0v4.001A1 1 0 0 0 9 16");
}

:global(.sfso60bve) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Zm10 10a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2Z");
}

</style>
