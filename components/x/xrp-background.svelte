<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path class="cjiy9cbiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:xrp-background" {...props}></Icon>
<style>
:global(.cjiy9cbiy) {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.654 5h2.315l-4.817 5.139A4.37 4.37 0 0 1 12 11.505a4.37 4.37 0 0 1-3.152-1.366L4.023 5h2.323l3.656 3.936c1.07 1.136 2.925 1.136 3.996 0zM6.315 18.992H4l4.847-5.124a4.38 4.38 0 0 1 3.156-1.366a4.38 4.38 0 0 1 3.156 1.367L20 18.999h-2.316l-3.678-3.92c-1.071-1.135-2.925-1.135-3.996 0z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

</style>
