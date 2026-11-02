<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ejfagnbsy"/><path class="pfpll4bfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stethoscope-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ejfagnbsy) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 12.829V15a7 7 0 1 1-14 0a1 1 0 0 1 2 0a5 5 0 1 0 10 0v-2.171a3 3 0 1 1 2 0M19 11a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

:global(.pfpll4bfw) {
  d: path("M6 3v2a1 1 0 0 1-2 0v6a3 3 0 1 0 6 0V5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0h1a1 1 0 0 1 1 1v7a5 5 0 0 1-10 0V4a1 1 0 0 1 1-1h1a1 1 0 0 1 2 0");
}

</style>
