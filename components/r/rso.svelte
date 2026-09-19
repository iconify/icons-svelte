<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ct2tujbuh"/><path class="bga6_xriz"/><circle class="izrvgmbxq"/><path class="y37dv-3eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rso" {...props}></Icon>
<style>
:global(.bga6_xriz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.603 28.78H16.398l7.603-13.168z");
}

:global(.ct2tujbuh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 10.549l.623 19.977l13.847 6.3l-.113 1.418l16.74 4.37l4.371-6.299l-1.418-11.407l2.95-3.916l-2.213-10.5L23.66 8.62l-.738-3.234z");
}

:global(.izrvgmbxq) {
  cx: 23.955px;
  cy: 26.934px;
  r: 0.75px;
  fill: currentColor;
}

:global(.y37dv-3eq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.955 19.95v5.194");
}

</style>
