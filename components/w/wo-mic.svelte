<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dr18h6byf"/><path class="rkz4pmrct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wo-mic" {...props}></Icon>
<style>
:global(.dr18h6byf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a8.503 8.503 0 0 1 8.503 8.503v10.512A8.503 8.503 0 0 1 24 32.017h0a8.503 8.503 0 0 1-8.503-8.502V13.003A8.503 8.503 0 0 1 24 4.5");
}

:global(.rkz4pmrct) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.855 26.045a13.387 13.387 0 0 0 26.29 0M24 36.898V43.5m-13.145 0h26.29");
}

</style>
