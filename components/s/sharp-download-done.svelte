<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg7gi1b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-download-done" {...props}></Icon>
<style>
:global(.sg7gi1b0a) {
  fill: currentColor;
  d: path("M5 18h14v2H5zm4.6-2.7L5 10.7l2-1.9l2.6 2.6L17 4l2 2z");
}

</style>
