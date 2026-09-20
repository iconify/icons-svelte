<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="oz2masbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:subset-proper-of-bold" {...props}></Icon>
<style>
:global(.oz2masbet) {
  fill: currentColor;
  d: path("M212 208a12 12 0 0 1-12 12h-72a92 92 0 0 1 0-184h72a12 12 0 0 1 0 24h-72a68 68 0 0 0 0 136h72a12 12 0 0 1 12 12");
}

</style>
