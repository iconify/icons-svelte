<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ga9nhbbxi"/><path class="j-759vb2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:venus-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ga9nhbbxi) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 8a6 6 0 1 1 12 0A6 6 0 0 1 6 8");
}

:global(.j-759vb2i) {
  d: path("M13 16h2a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0v-3H9a1 1 0 0 1 0-2h2v-3a1 1 0 0 1 2 0Z");
}

</style>
