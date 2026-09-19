<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="yg3x3ublv"/><circle class="ap76noi5m"/><circle class="sjg9j274c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-scatter-plot" {...props}></Icon>
<style>
:global(.ap76noi5m) {
  cx: 11px;
  cy: 6px;
  r: 3px;
  fill: currentColor;
}

:global(.sjg9j274c) {
  cx: 16.6px;
  cy: 17.6px;
  r: 3px;
  fill: currentColor;
}

:global(.yg3x3ublv) {
  cx: 7px;
  cy: 14px;
  r: 3px;
  fill: currentColor;
}

</style>
