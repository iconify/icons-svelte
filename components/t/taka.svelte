<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wh2yd8b9a"/><path class="ptdsr2bxu"/><path class="rb-wkfb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:taka" {...props}></Icon>
<style>
:global(.ptdsr2bxu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.452 12.93v-2.507h19.096v27.154h-6.564");
}

:global(.rb-wkfb1r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.403 8.036V5.53H42.5v27.153h-6.564");
}

:global(.wh2yd8b9a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.317h19.097V42.47H5.5z");
}

</style>
