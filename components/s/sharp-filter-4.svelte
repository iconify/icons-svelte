<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7zzzxb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-filter-4" {...props}></Icon>
<style>
:global(.d7zzzxb4g) {
  fill: currentColor;
  d: path("M3 5H1v18h18v-2H3zm12 10h2V5h-2v4h-2V5h-2v6h4zm8-14H5v18h18zm-2 16H7V3h14z");
}

</style>
