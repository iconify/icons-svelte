<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rewx-801w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-format-strikethrough" {...props}></Icon>
<style>
:global(.rewx-801w) {
  fill: currentColor;
  d: path("M3 12h18v2H3zm11-2V7h5V4H5v3h5v3zm-4 6h4v3h-4z");
}

</style>
