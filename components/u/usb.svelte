<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g5v-l6bxf"/><circle class="h-zk0mb_w"/><circle class="kfpgbbbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:usb" {...props}></Icon>
<style>
:global(.g5v-l6bxf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.125 36.5v-26m-3 0l3-6l3 6zm3 18.407l8.5-4.907v-3m-8.5 11.907L15.625 28v-3m14.25-9.501h5.5v5.5h-5.5z");
}

:global(.h-zk0mb_w) {
  cx: 24.125px;
  cy: 40px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.kfpgbbbhw) {
  cx: 15.625px;
  cy: 21.999px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
