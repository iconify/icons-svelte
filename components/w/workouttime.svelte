<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="at_8vrn9p"/><circle class="wzg4aubzr"/><path class="u2m5vccdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:workouttime" {...props}></Icon>
<style>
:global(.at_8vrn9p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 42.46A21.51 21.51 0 0 1 8.72 8.87M24 2.5a21.52 21.52 0 0 1 20.57 27.78M24 2.5v15.72m-1.77 4.01l-8.28-8.28");
}

:global(.u2m5vccdq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28 31c-2.75 5.73 7.77 12.2 8.52 12.2S47.79 36.74 45 31c-1.21-2.21-4.71-5.2-8.51 0c-2.44-3.85-6.49-3.74-8.49 0");
}

:global(.wzg4aubzr) {
  cx: 24px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
