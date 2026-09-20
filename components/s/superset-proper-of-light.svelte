<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yrtjkw1cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:superset-proper-of-light" {...props}></Icon>
<style>
:global(.yrtjkw1cf) {
  fill: currentColor;
  d: path("M222 128a86.1 86.1 0 0 1-86 86H64a6 6 0 0 1 0-12h72a74 74 0 0 0 0-148H64a6 6 0 0 1 0-12h72a86.1 86.1 0 0 1 86 86");
}

</style>
