<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="oissuxj4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:thermoworks" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.oissuxj4v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.608 38.5a15.05 15.05 0 0 0 1.313-6.601c0-7.894-3.842-7.894-3.842-15.788A15.1 15.1 0 0 1 23.395 9.5m8.792 29a15.05 15.05 0 0 0 1.313-6.601c0-7.894-3.842-7.894-3.842-15.787A15.1 15.1 0 0 1 30.974 9.5m-13.945 29a15.05 15.05 0 0 0 1.313-6.601c0-7.894-3.842-7.894-3.842-15.788A15.1 15.1 0 0 1 15.815 9.5");
}

</style>
