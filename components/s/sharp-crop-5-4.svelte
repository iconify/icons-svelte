<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f59_i0grv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-crop-5-4" {...props}></Icon>
<style>
:global(.f59_i0grv) {
  fill: currentColor;
  d: path("M21 4H3v16h18zm-2 14H5V6h14z");
}

</style>
