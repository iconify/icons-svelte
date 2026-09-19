<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="graezgbrw"/><path class="dv9_d-oso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tubular" {...props}></Icon>
<style>
:global(.dv9_d-oso) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.51 10.49l21.123 13.46L5.5 37.51z");
}

:global(.graezgbrw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.189 10.49L42.5 23.95L19.013 37.51");
}

</style>
