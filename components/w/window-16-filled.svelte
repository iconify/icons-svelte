<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d5_cnacqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:window-16-filled" {...props}></Icon>
<style>
:global(.d5_cnacqi) {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM3 6v5.5A1.5 1.5 0 0 0 4.5 13h7a1.5 1.5 0 0 0 1.5-1.5V6z");
}

</style>
