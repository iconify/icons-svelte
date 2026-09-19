<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxpshhbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-image" {...props}></Icon>
<style>
:global(.cxpshhbea) {
  fill: currentColor;
  d: path("M21 21V3H3v18zM8.5 13.5l2.5 3.01L14.5 12l4.5 6H5z");
}

</style>
