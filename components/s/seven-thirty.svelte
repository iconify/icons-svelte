<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pdpxocbiv"/><circle class="rt_37l3dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:seven-thirty" {...props}></Icon>
<style>
:global(.pdpxocbiv) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m4 30c0 1.477-.81 2.753-2 3.445V58h-4V36.855L20.857 46L18 43.141L28.142 33A4 4 0 0 1 28 32c0-1.478.81-2.753 2-3.446V26h4v1.143L35.143 26L38 28.855l-2.142 2.142c.083.323.142.655.142 1.003");
}

:global(.rt_37l3dj) {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
