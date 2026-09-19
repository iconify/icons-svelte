<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l3hbskbwk"/><circle class="pscdx3bwd"/><circle class="wq5_62bzd"/><path class="mmcv3qb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:xmeye" {...props}></Icon>
<style>
:global(.l3hbskbwk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.553 11.221v24.273c0 2.216-1.784 4-4 4H10.774");
}

:global(.mmcv3qb9t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.006L24 8.506l18.5 18.5");
}

:global(.pscdx3bwd) {
  cx: 24px;
  cy: 27.934px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wq5_62bzd) {
  cx: 26px;
  cy: 25.934px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
