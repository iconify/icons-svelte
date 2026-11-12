<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xyta0kxfq"/><path class="syq-kg8rw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:warehouse-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.syq-kg8rw) {
  d: path("M21 22H3a1 1 0 0 1 0-2h5v-7a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v7h5a1 1 0 0 1 0 2m-7-6v-2h-4v2Zm-4 4h4v-2h-4Z");
}

:global(.xyta0kxfq) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 21v-9c0-1.693 1.069-3.152 2.553-3.894l4-2A1 1 0 0 1 11 6h2c.155 0 .308.036.447.106l4 2C18.931 8.848 20 10.307 20 12v9a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1");
}

</style>
