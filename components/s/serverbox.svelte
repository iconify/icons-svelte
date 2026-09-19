<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a0i_k8sfs"/><circle class="tkz3bkbvn"/><circle class="o37rxvb3r"/><path class="tn5tgyaog"/><circle class="btb1lkbit"/><circle class="qfo_199rn"/><path class="p2v5hcklt"/><circle class="ovm9-rd9o"/><path class="mxogmygbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:serverbox" {...props}></Icon>
<style>
:global(.a0i_k8sfs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.662 4.5h22.674a3.453 3.453 0 0 1 3.452 3.453v3.274a3.453 3.453 0 0 1-3.452 3.452H12.662a3.453 3.453 0 0 1-3.453-3.452q0 0 0 0V7.953A3.453 3.453 0 0 1 12.662 4.5");
}

:global(.btb1lkbit) {
  cx: 14.386px;
  cy: 24.329px;
  r: 1.538px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mxogmygbt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 29.42v5.76m4.16 4.16l10.806-.096m-19.126.001l-10.806.096");
}

:global(.o37rxvb3r) {
  cx: 20.628px;
  cy: 9.589px;
  r: 1.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ovm9-rd9o) {
  cx: 23.999px;
  cy: 39.34px;
  r: 4.16px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.p2v5hcklt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.808 19.24v-4.56m22.383 4.56v-4.56");
}

:global(.qfo_199rn) {
  cx: 20.628px;
  cy: 24.329px;
  r: 1.538px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tkz3bkbvn) {
  cx: 14.386px;
  cy: 9.589px;
  r: 1.538px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tn5tgyaog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.662 19.24h22.674a3.453 3.453 0 0 1 3.452 3.453v3.274a3.453 3.453 0 0 1-3.452 3.452H12.662a3.453 3.453 0 0 1-3.453-3.452q0 0 0 0v-3.274a3.453 3.453 0 0 1 3.453-3.453");
}

</style>
