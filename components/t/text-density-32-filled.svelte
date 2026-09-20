<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ko1z8-bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-density-32-filled" {...props}></Icon>
<style>
:global(.ko1z8-bof) {
  fill: currentColor;
  d: path("M17 3a1 1 0 1 0-2 0v26a1 1 0 1 0 2 0zm2.5 5h6a2.5 2.5 0 0 1 0 5h-6zm6 11h-6v5h6a2.5 2.5 0 0 0 0-5M3 5a1 1 0 0 0 0 2h10.5V5zM2 26a1 1 0 0 1 1-1h10.5v2H3a1 1 0 0 1-1-1m1-6a1 1 0 1 0 0 2h10.5v-2zm-1-4a1 1 0 0 1 1-1h10.5v2H3a1 1 0 0 1-1-1m1-6a1 1 0 1 0 0 2h10.5v-2z");
}

</style>
