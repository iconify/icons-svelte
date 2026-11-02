<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="umg5cabuu"/><path class="x6s2sfbnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skull-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.umg5cabuu) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 16.35V19a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2.65A8.81 8.81 0 0 1 6.052 4.501A8.81 8.81 0 0 1 19 16.35");
}

:global(.x6s2sfbnj) {
  d: path("M7 12a2 2 0 1 1 3.999-.001A2 2 0 0 1 7 12m6 0a2 2 0 1 1 3.999-.001A2 2 0 0 1 13 12m-2 6v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m4 0v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0");
}

</style>
