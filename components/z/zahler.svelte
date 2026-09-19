<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l_pq1jbni"/><rect class="cn21r53gf"/><rect class="h0ur40ynx"/><path class="be39vcq8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zahler" {...props}></Icon>
<style>
:global(.be39vcq8i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.5 42.5h-11");
}

:global(.cn21r53gf) {
  width: 15px;
  height: 15px;
  x: 3.5px;
  y: 29.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

:global(.h0ur40ynx) {
  width: 15px;
  height: 15px;
  x: 29.5px;
  y: 29.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

:global(.l_pq1jbni) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 29.5v-20a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v20M19 16.723L24 14m0 0v20m9.5 3h7m-33 0h7M11 33.5v7");
}

</style>
