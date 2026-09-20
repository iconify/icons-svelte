<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a0kfnif2f"/><path class="wtwkxebia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wifiautomatic" {...props}></Icon>
<style>
:global(.a0kfnif2f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 23.51a14.44 14.44 0 0 0-18.45-.05v.05m9.2 3.54a7.61 7.61 0 1 0 7.61 7.61A7.61 7.61 0 0 0 24 27.05m14-9.36a22 22 0 0 0-28 0");
}

:global(.wtwkxebia) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.48 12.4a29 29 0 0 0-37 0m15.23 26.47l3.39-8.44m3.24 8.47l-3.24-8.47m2.16 5.63h-4.43");
}

</style>
