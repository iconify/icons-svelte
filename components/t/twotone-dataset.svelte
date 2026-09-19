<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwa0siozh"/><path class="jfg345bbh"/><path class="bn6ebpb5p"/><path class="zt59mfkop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-dataset" {...props}></Icon>
<style>
:global(.bn6ebpb5p) {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

:global(.jfg345bbh) {
  fill: currentColor;
  d: path("M7 13h4v4H7zm6 0h4v4h-4z");
}

:global(.pwa0siozh) {
  fill: currentColor;
  d: path("M5 19h14V5H5zm8-12h4v4h-4zm0 6h4v4h-4zM7 7h4v4H7zm0 6h4v4H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.zt59mfkop) {
  fill: currentColor;
  d: path("M7 7h4v4H7zm6 0h4v4h-4z");
}

</style>
