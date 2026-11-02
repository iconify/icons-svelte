<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yu5507bhi"/><path class="rqatjzbho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trash-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.rqatjzbho) {
  d: path("M7 3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v2h3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3Zm8 2V4H9v1Z");
}

:global(.yu5507bhi) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v15a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Z");
}

</style>
