<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pjl2xdbsb"/><path class="gzt1w8bis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:search-check-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gzt1w8bis) {
  d: path("M7.707 9.293L9 10.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414m8 5l6 6a.999.999 0 1 1-1.414 1.414l-6-6a.999.999 0 1 1 1.414-1.414");
}

:global(.pjl2xdbsb) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

</style>
