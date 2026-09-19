<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq33o9bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-insert-invitation" {...props}></Icon>
<style>
:global(.oq33o9bjz) {
  fill: currentColor;
  d: path("M17 12h-5v5h5zM16 1v2H8V1H6v2H3.01v18H21V3h-3V1zm3 18H5V8h14z");
}

</style>
