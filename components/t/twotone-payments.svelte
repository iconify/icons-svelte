<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjedm9s5c"/><path class="zbh6bbchh"/><path class="dw_42rb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-payments" {...props}></Icon>
<style>
:global(.dw_42rb8k) {
  fill: currentColor;
  d: path("M10 7c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3m13 0v11c0 1.1-.9 2-2 2H4v-2h17V7z");
}

:global(.zbh6bbchh) {
  fill: currentColor;
  d: path("M17 4H3c-1.1 0-2 .9-2 2v8c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2M3 14V6h14v8z");
}

:global(.zjedm9s5c) {
  fill: currentColor;
  d: path("M17 6H3v8h14zm-7 7c-1.66 0-3-1.34-3-3s1.34-3 3-3s3 1.34 3 3s-1.34 3-3 3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
