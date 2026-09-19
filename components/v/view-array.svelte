<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws7vmacpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:view-array" {...props}></Icon>
<style>
:global(.ws7vmacpo) {
  fill: currentColor;
  d: path("M21 5h-3v14h3zm-4 0H7v14h10zM6 5H3v14h3z");
}

</style>
