<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyip1_bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-local-post-office" {...props}></Icon>
<style>
:global(.qyip1_bgz) {
  fill: currentColor;
  d: path("M22 4H2.01v16H22zm-2 4l-8 5l-8-5V6l8 5l8-5z");
}

</style>
