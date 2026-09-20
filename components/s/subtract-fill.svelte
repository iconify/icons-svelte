<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lrnzat1gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:subtract-fill" {...props}></Icon>
<style>
:global(.lrnzat1gd) {
  fill: currentColor;
  d: path("M174.63 81.35a80 80 0 1 0-93.28 93.28a80 80 0 1 0 93.28-93.28M96 160a64 64 0 1 1 64-64a64.07 64.07 0 0 1-64 64");
}

</style>
