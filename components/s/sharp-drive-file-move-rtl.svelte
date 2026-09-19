<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxu3n4l1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-drive-file-move-rtl" {...props}></Icon>
<style>
:global(.qxu3n4l1h) {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zM12 17l-4-4l4-4v3h4v2h-4z");
}

</style>
