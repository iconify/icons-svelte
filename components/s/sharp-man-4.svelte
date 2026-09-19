<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkxyq6jya"/><circle class="yfz3w9lrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-man-4" {...props}></Icon>
<style>
:global(.hkxyq6jya) {
  fill: currentColor;
  d: path("M7.96 7L10 22h4l2.04-15z");
}

:global(.yfz3w9lrl) {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

</style>
