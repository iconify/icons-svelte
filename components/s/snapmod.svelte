<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="ytezkibsj"/><path class="y_jo5kxvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:snapmod" {...props}></Icon>
<style>
:global(.y_jo5kxvu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.644 14.009z");
}

:global(.ytezkibsj) {
  width: 21.7px;
  height: 39px;
  x: 13.15px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.022px;
}

</style>
