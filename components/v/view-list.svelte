<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dah6a880o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:view-list" {...props}></Icon>
<style>
:global(.dah6a880o) {
  fill: currentColor;
  d: path("M3 14h4v-4H3zm0 5h4v-4H3zM3 9h4V5H3zm5 5h13v-4H8zm0 5h13v-4H8zM8 5v4h13V5z");
}

</style>
