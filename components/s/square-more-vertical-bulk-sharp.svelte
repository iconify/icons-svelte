<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="td1bzxb2d"/><path class="w0d5zzb4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-more-vertical-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.td1bzxb2d) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

:global(.w0d5zzb4m) {
  d: path("M12.01 7a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
