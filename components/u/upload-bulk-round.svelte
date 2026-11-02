<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a06aaqtap"/><path class="jxq-ihbak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:upload-bulk-round" {...props}></Icon>
<style>
:global(.a06aaqtap) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 19h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jxq-ihbak) {
  d: path("M13 6.414V16a1 1 0 0 1-2 0V6.414L8.707 8.707a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Z");
}

</style>
