<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path class="mc5x88bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-camera-alt" {...props}></Icon>
<style>
:global(.mc5x88bqt) {
  fill: currentColor;
  d: path("M16.83 4L15 2H9L7.17 4H2v16h20V4zM12 17c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
}

:global(.v4i2ew1ke) {
  cx: 12px;
  cy: 12px;
  r: 3px;
  fill: currentColor;
}

</style>
