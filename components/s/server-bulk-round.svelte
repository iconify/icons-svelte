<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e7wyaz_gg"/><path class="u_zqldigq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.e7wyaz_gg) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m0 10h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8");
}

:global(.u_zqldigq) {
  d: path("M7 6h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m0 10h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>
