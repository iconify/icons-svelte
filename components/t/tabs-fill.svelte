<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="oyw-a4ntf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:tabs-fill" {...props}></Icon>
<style>
:global(.oyw-a4ntf) {
  fill: currentColor;
  d: path("M256 168a8 8 0 0 1-8 8H8a8 8 0 0 1-7.63-10.4l22.26-74.2A15.89 15.89 0 0 1 38 80h84.1a15.89 15.89 0 0 1 15.32 11.4L158 160h15.3l-22.51-74.85a4 4 0 0 1 3.83-5.15h15.43a16 16 0 0 1 15.32 11.4L206 160h15.3l-22.51-74.85a4 4 0 0 1 3.83-5.15h15.43a16 16 0 0 1 15.32 11.4l22.26 74.18A8.1 8.1 0 0 1 256 168");
}

</style>
