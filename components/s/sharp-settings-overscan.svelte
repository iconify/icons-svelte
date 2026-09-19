<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw13r1bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-settings-overscan" {...props}></Icon>
<style>
:global(.jw13r1bad) {
  fill: currentColor;
  d: path("M12.01 5.5L10 8h4zM18 10v4l2.5-1.99zM6 10l-2.5 2.01L6 14zm8 6h-4l2.01 2.5zm9-13H1v18h22zm-2 16.01H3V4.99h18z");
}

</style>
