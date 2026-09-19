<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="xirggixkk"/><path class="j4pch3but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vip-access" {...props}></Icon>
<style>
:global(.j4pch3but) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.139 19.695a25.8 25.8 0 0 1 9.968 11.283c2.243-4.282 12.507-19.643 19.44-25.42");
}

:global(.xirggixkk) {
  cx: 23.453px;
  cy: 24px;
  r: 20px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
