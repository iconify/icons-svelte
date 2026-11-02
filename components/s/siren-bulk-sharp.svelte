<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kdxtjmelr"/><path class="uwqmtgb0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:siren-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kdxtjmelr) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h2v-3a5 5 0 0 1 10 0v3Z");
}

:global(.uwqmtgb0c) {
  d: path("M13 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-8.293-.707l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414m16 1.414l-2 2a1 1 0 0 1-1.414-1.414l2-2a.999.999 0 1 1 1.414 1.414M13 13v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
