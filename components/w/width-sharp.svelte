<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmlr_lb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:width-sharp" {...props}></Icon>
<style>
:global(.tmlr_lb3m) {
  fill: currentColor;
  d: path("m7 16l-4-4l4-4l1.425 1.4l-1.6 1.6h10.35L15.6 9.4L17 8l4 4l-4 4l-1.4-1.4l1.575-1.6H6.825L8.4 14.6z");
}

</style>
