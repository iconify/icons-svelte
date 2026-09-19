<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="xsqzccc6b"/><path class="dj_fbxoac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tfl-go" {...props}></Icon>
<style>
:global(.dj_fbxoac) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24h43");
}

:global(.xsqzccc6b) {
  cx: 24px;
  cy: 24px;
  r: 16.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
