<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="cmqrkgb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:toggle-right-28-regular" {...props}></Icon>
<style>
:global(.cmqrkgb0n) {
  fill: currentColor;
  d: path("M19 17a3 3 0 1 1 0-6a3 3 0 0 1 0 6m1-9a6 6 0 0 1 0 12H8A6 6 0 0 1 8 8zm4.5 6A4.5 4.5 0 0 0 20 9.5H8a4.5 4.5 0 1 0 0 9h12a4.5 4.5 0 0 0 4.5-4.5");
}

</style>
