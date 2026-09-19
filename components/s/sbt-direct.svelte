<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="vn93xx72a"/><circle class="fg8whccal"/><path class="ul4_m6cqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sbt-direct" {...props}></Icon>
<style>
:global(.fg8whccal) {
  cx: 34.708px;
  cy: 34.492px;
  r: 7.792px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ul4_m6cqi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.084 34.492V5.716m5.832 28.776V14.465");
}

:global(.vn93xx72a) {
  cx: 13.292px;
  cy: 34.492px;
  r: 7.792px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
