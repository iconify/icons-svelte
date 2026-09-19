<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybsa6tb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-subtitles-off" {...props}></Icon>
<style>
:global(.ybsa6tb7h) {
  fill: currentColor;
  d: path("m6.83 4l8 8H20v2h-3.17L22 19.17V4zm-5.79-.13l.96.96V20h15.17l2.96 2.96l1.41-1.41L2.45 2.45zM4 12h4v2H4zm0 4h9.17l.83.83V18H4z");
}

</style>
