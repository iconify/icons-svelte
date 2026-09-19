<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzvno1w7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-email" {...props}></Icon>
<style>
:global(.uzvno1w7h) {
  fill: currentColor;
  d: path("M22 4H2v16h20zm-2 4l-8 5l-8-5V6l8 5l8-5z");
}

</style>
