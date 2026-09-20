<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pjwot1bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:shape-subtract-16-filled" {...props}></Icon>
<style>
:global(.pjwot1bjn) {
  fill: currentColor;
  d: path("M3 2.268A2 2 0 0 0 2 4v5a2 2 0 0 0 .01.204A2.004 2.004 0 0 0 4 11h1v1a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2h-1V4a2 2 0 0 0-2-2H4a2 2 0 0 0-1 .268M6 7a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1z");
}

</style>
