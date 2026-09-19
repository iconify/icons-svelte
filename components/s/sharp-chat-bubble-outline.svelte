<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv-82bbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-chat-bubble-outline" {...props}></Icon>
<style>
:global(.dv-82bbeb) {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16zm-2 14H6l-2 2V4h16z");
}

</style>
