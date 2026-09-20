<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h_aqshbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:rss-simple-light" {...props}></Icon>
<style>
:global(.h_aqshbbh) {
  fill: currentColor;
  d: path("M222 192a6 6 0 0 1-12 0c0-80.5-65.5-146-146-146a6 6 0 0 1 0-12c87.12 0 158 70.88 158 158M64 106a6 6 0 0 0 0 12a74.09 74.09 0 0 1 74 74a6 6 0 0 0 12 0a86.1 86.1 0 0 0-86-86m4 72a10 10 0 1 0 10 10a10 10 0 0 0-10-10");
}

</style>
