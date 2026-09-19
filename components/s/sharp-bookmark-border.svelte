<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7qrhabmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-bookmark-border" {...props}></Icon>
<style>
:global(.e7qrhabmy) {
  fill: currentColor;
  d: path("M19 3H5v18l7-3l7 3zm-2 15l-5-2.18L7 18V5h10z");
}

</style>
