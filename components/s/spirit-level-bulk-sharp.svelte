<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zuq7nzbyd"/><path class="jv9_svena"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:spirit-level-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jv9_svena) {
  d: path("M8 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m10 4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm-7-4h2a2 2 0 1 1 0 4h-2a2 2 0 1 1 0-4");
}

:global(.zuq7nzbyd) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6h18a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1");
}

</style>
