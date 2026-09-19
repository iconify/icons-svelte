<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atg1l9e9y"/><path class="b3h8yx8_x"/><path class="xugrx5b8f"/><path class="vja0g088d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-margin" {...props}></Icon>
<style>
:global(.atg1l9e9y) {
  fill: currentColor;
  d: path("M5 19h14V5H5zM15 7h2v2h-2zm0 4h2v2h-2zm-4-4h2v2h-2zm0 4h2v2h-2zM7 7h2v2H7zm0 4h2v2H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.b3h8yx8_x) {
  fill: currentColor;
  d: path("M7 7h2v2H7zm0 4h2v2H7z");
}

:global(.vja0g088d) {
  fill: currentColor;
  d: path("M11 7h2v2h-2zm4 4h2v2h-2zm-4 0h2v2h-2zm4-4h2v2h-2z");
}

:global(.xugrx5b8f) {
  fill: currentColor;
  d: path("M3 3v18h18V3zm16 16H5V5h14z");
}

</style>
