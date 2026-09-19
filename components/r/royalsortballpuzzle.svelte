<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="k7--nbc3n"/><circle class="j4wgh7jgi"/><path class="v4axtobty"/><circle class="pgp1_4tpn"/><circle class="sgz5n_ozp"/><path class="dq-4__bbc"/><circle class="xwh4lcb6r"/><path class="tfpse3nhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:royalsortballpuzzle" {...props}></Icon>
<style>
:global(.dq-4__bbc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.138 16.648v19.305a5.18 5.18 0 1 0 10.362 0V16.648Z");
}

:global(.j4wgh7jgi) {
  cx: 10.681px;
  cy: 35.614px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.k7--nbc3n) {
  cx: 24px;
  cy: 9.867px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.pgp1_4tpn) {
  cx: 37.319px;
  cy: 35.614px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sgz5n_ozp) {
  cx: 37.319px;
  cy: 26.988px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tfpse3nhf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.82 16.648v19.305a5.18 5.18 0 1 0 10.36 0V16.648Z");
}

:global(.v4axtobty) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16.648v19.305a5.18 5.18 0 1 0 10.362 0V16.648Z");
}

:global(.xwh4lcb6r) {
  cx: 24px;
  cy: 35.614px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
