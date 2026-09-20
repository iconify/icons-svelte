<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x29ts1h7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:send-32-regular" {...props}></Icon>
<style>
:global(.x29ts1h7h) {
  fill: currentColor;
  d: path("M2.078 3.965c-.407-1.265.91-2.395 2.099-1.801l24.994 12.495c1.106.553 1.106 2.13 0 2.684L4.177 29.838c-1.188.594-2.506-.536-2.099-1.801L5.95 16.001zm5.65 13.036L4.347 27.517l23.037-11.516L4.346 4.485L7.73 15H19a1 1 0 1 1 0 2z");
}

</style>
