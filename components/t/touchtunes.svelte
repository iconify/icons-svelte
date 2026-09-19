<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ao501tbcv"/><circle class="anygj995f"/><circle class="sd8zx4o6o"/><circle class="o7vxk9bes"/><circle class="shzpu1bin"/><circle class="lr1fou36u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:touchtunes" {...props}></Icon>
<style>
:global(.anygj995f) {
  cx: 12.131px;
  cy: 10.295px;
  r: 4.795px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ao501tbcv) {
  cx: 35.869px;
  cy: 24px;
  r: 4.795px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lr1fou36u) {
  cx: 24px;
  cy: 30.852px;
  r: 4.795px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.o7vxk9bes) {
  cx: 12.131px;
  cy: 24px;
  r: 4.795px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sd8zx4o6o) {
  cx: 12.131px;
  cy: 37.705px;
  r: 4.795px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.shzpu1bin) {
  cx: 24px;
  cy: 17.148px;
  r: 4.795px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
