<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro3u7ld2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-picture-in-picture" {...props}></Icon>
<style>
:global(.ro3u7ld2q) {
  fill: currentColor;
  d: path("M19 7h-8v6h8zm4-4H1v17.98h22zm-2 16.01H3V4.98h18z");
}

</style>
