<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="gkbzx0-9v"/><path class="p3t1t0bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:smartphone" {...props}></Icon>
<style>
:global(.gkbzx0-9v) {
  width: 23px;
  height: 39px;
  x: 12.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.p3t1t0bmr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 41.5h7");
}

</style>
