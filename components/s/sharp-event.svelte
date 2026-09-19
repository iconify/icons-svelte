<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zisgoccru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-event" {...props}></Icon>
<style>
:global(.zisgoccru) {
  fill: currentColor;
  d: path("M17 13h-5v5h5zM16 2v2H8V2H6v2H3.01L3 22h18V4h-3V2zm3 18H5V9h14z");
}

</style>
