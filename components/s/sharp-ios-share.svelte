<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxdrrybsz"/><path class="pj6ewyu5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-ios-share" {...props}></Icon>
<style>
:global(.pj6ewyu5x) {
  fill: currentColor;
  d: path("M11 16h2V5h3l-4-4l-4 4h3z");
}

:global(.uxdrrybsz) {
  fill: currentColor;
  d: path("M20 8h-5v2h3v11H6V10h3V8H4v15h16z");
}

</style>
