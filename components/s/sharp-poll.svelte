<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcqia5evy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-poll" {...props}></Icon>
<style>
:global(.dcqia5evy) {
  fill: currentColor;
  d: path("M3 3v18h18V3zm6 14H7v-7h2zm4 0h-2V7h2zm4 0h-2v-4h2z");
}

</style>
