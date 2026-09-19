<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs8_ejdrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-volume-mute" {...props}></Icon>
<style>
:global(.xs8_ejdrv) {
  fill: currentColor;
  d: path("M7 9v6h4l5 5V4l-5 5z");
}

</style>
