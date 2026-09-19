<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iax8lxkge"/><path class="q_q0_q9an"/><circle class="kzf5v7bdq"/><path class="gmbgj2b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:slovenskaposta" {...props}></Icon>
<style>
:global(.gmbgj2b9z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.982 37.867l10.784-7.594m25.395 7.588L30.745 29.99M5.553 10.161s3.038 14.886 11.237 20.06c0 0 8.177 4.618 13.825-.554c0 0 6.31-7.149.304-13.822c0 0-5.961-7.103-14.043.34");
}

:global(.iax8lxkge) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 9.396h37v29.208h-37z");
}

:global(.kzf5v7bdq) {
  cx: 23.836px;
  cy: 22.709px;
  r: 4.907px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.q_q0_q9an) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.955 10.045s-1.657 8.722-4.42 11.135m8.943-10.935s-1.5 13.057-10.803 19.163M16.5 9.58s-.366 11.77 3.117 15.704");
}

</style>
