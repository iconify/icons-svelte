<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n-c5ftbdr"/><path class="yd5rdxbnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:signpost-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.n-c5ftbdr) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 5c.265 0 .52.105.707.293l3 3a1 1 0 0 1 0 1.414l-3 3A1 1 0 0 1 17 13H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1Z");
}

:global(.yd5rdxbnk) {
  d: path("M13 3v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m0 9v9a1 1 0 0 1-2 0v-9a1 1 0 0 1 2 0");
}

</style>
