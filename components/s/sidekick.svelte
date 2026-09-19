<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="guzb0weuh"/><circle class="h8x59olcc"/><path class="jce8wccoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sidekick" {...props}></Icon>
<style>
:global(.guzb0weuh) {
  cx: 5.5px;
  cy: 42.5px;
  r: 0.75px;
  fill: currentColor;
}

:global(.h8x59olcc) {
  cx: 42.5px;
  cy: 5.5px;
  r: 0.75px;
  fill: currentColor;
}

:global(.jce8wccoy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 5.5H16.75a9.25 9.25 0 0 0 0 18.5h14.5a9.25 9.25 0 0 1 0 18.5H8.5");
}

</style>
