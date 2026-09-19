<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="dhzntztny"/><path class="nfvk9d-0v"/><path class="lsu4oxb2j"/><circle class="v_-ncqb8g"/><path class="dsciqobcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:transitnow" {...props}></Icon>
<style>
:global(.dhzntztny) {
  cx: 17.07px;
  cy: 35.78px;
  r: 2.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.dsciqobcr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.36 14.61v9.76l-3.61 4.66h-15.5l-3.61-4.66v-9.76z");
}

:global(.lsu4oxb2j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.92 4.5H16.08a7.58 7.58 0 0 0-7.58 7.58v19a3 3 0 0 0 .36 1.43l4.78 9a3.78 3.78 0 0 0 3.34 2H31a3.78 3.78 0 0 0 3.34-2l4.78-9a3 3 0 0 0 .36-1.43v-19a7.58 7.58 0 0 0-7.56-7.58");
}

:global(.nfvk9d-0v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.64 9.98h22.72v4.63H12.64z");
}

:global(.v_-ncqb8g) {
  cx: 30.93px;
  cy: 35.78px;
  r: 2.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
