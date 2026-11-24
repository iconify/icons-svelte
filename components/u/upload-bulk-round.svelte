<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m310_5mrs"/><path class="jxq-ihbak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:upload-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jxq-ihbak) {
  d: path("M13 6.414V16a1 1 0 0 1-2 0V6.414L8.707 8.707a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Z");
}

:global(.m310_5mrs) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 19h8a3 3 0 0 0 3-3a1 1 0 0 1 2 0a5 5 0 0 1-1.464 3.536A4.98 4.98 0 0 1 16 21H8a4.98 4.98 0 0 1-3.536-1.464A5 5 0 0 1 3 16a1 1 0 0 1 2 0a3 3 0 0 0 3 3");
}

</style>
