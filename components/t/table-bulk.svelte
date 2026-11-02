<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dcvx-qzrl"/><path class="zwbm9rbyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dcvx-qzrl) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

:global(.zwbm9rbyc) {
  d: path("M13 4v4h7a1 1 0 0 1 0 2h-7v4h7a1 1 0 0 1 0 2h-7v4a1 1 0 0 1-2 0v-4H4a1 1 0 0 1 0-2h7v-4H4a1 1 0 0 1 0-2h7V4a1 1 0 0 1 2 0");
}

</style>
