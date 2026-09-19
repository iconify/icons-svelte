<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu_-64b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-crop-landscape" {...props}></Icon>
<style>
:global(.vu_-64b-b) {
  fill: currentColor;
  d: path("M21 5H3v14h18zm-2 12H5V7h14z");
}

</style>
