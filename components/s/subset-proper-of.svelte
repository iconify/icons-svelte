<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y6_g_obrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:subset-proper-of" {...props}></Icon>
<style>
:global(.y6_g_obrh) {
  fill: currentColor;
  d: path("M208 208a8 8 0 0 1-8 8h-72a88 88 0 0 1 0-176h72a8 8 0 0 1 0 16h-72a72 72 0 0 0 0 144h72a8 8 0 0 1 8 8");
}

</style>
