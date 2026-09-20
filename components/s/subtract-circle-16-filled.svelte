<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpu8debip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:subtract-circle-16-filled" {...props}></Icon>
<style>
:global(.kpu8debip) {
  fill: currentColor;
  d: path("M1 8a7 7 0 1 1 14 0A7 7 0 0 1 1 8m4-.5a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1z");
}

</style>
