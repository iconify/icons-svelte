<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zg7micc9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:toggle-multiple-16-filled" {...props}></Icon>
<style>
:global(.zg7micc9s) {
  fill: currentColor;
  d: path("M5 1a3 3 0 0 0 0 6h6a3 3 0 1 0 0-6zm1 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0M5 8a3 3 0 0 0 0 6h6a3 3 0 1 0 0-6zm6 4a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
