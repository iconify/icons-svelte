<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dmj1_2btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:voicemail-20-regular" {...props}></Icon>
<style>
:global(.dmj1_2btg) {
  fill: currentColor;
  d: path("M8.732 9A2 2 0 1 1 7 8h6a2 2 0 1 1-1.732 1zM6 10a1 1 0 1 0 2 0a1 1 0 0 0-2 0m7-1a1 1 0 1 0 0 2a1 1 0 0 0 0-2M4 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zM3 6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1z");
}

</style>
