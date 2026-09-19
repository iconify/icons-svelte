<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvbuy1-8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-looks-two" {...props}></Icon>
<style>
:global(.mvbuy1-8c) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-6 10h-4v2h4v2H9v-6h4V9H9V7h6z");
}

</style>
