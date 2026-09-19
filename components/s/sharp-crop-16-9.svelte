<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8cs0naer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-crop-16-9" {...props}></Icon>
<style>
:global(.r8cs0naer) {
  fill: currentColor;
  d: path("M21 7H3v10h18zm-2 8H5V9h14z");
}

</style>
