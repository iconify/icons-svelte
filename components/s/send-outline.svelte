<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ncosbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:send-outline" {...props}></Icon>
<style>
:global(.w7ncosbop) {
  fill: currentColor;
  d: path("M3 20V4l19 8zm2-3l11.85-5L5 7v3.5l6 1.5l-6 1.5zm0 0V7z");
}

</style>
