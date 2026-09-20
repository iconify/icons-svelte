<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="vknbzj-_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:toggle-left-28-filled" {...props}></Icon>
<style>
:global(.vknbzj-_b) {
  fill: currentColor;
  d: path("M2 14a6 6 0 0 1 6-6h12a6 6 0 0 1 0 12H8a6 6 0 0 1-6-6m7 3a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
