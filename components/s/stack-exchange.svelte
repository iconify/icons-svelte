<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="nrovkrasm"/><path class="mycb99xao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:stack-exchange" {...props}></Icon>
<style>
:global(.mycb99xao) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.992 20.508h30.016M8.992 28.512h30.016M8.992 12.504h30.016M26.897 36.516V43.5l8.004-6.984");
}

:global(.nrovkrasm) {
  width: 30.016px;
  height: 32.016px;
  x: 8.992px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.041px;
}

</style>
