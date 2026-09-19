<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kfuyhebpv"/><circle class="fqai4-bkp"/><circle class="b_su2obet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:taxfix" {...props}></Icon>
<style>
:global(.b_su2obet) {
  cx: 36.5px;
  cy: 31.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.fqai4-bkp) {
  cx: 11.5px;
  cy: 16.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.kfuyhebpv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 38.5h13l22-29h-13z");
}

</style>
