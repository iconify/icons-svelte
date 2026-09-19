<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d_4rlubza"/><path class="q9skithoe"/><circle class="gdzi0w46r"/><circle class="xdxzu4omp"/><path class="yl647fboh"/><circle class="l7okhcc4d"/><circle class="sswktgbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shinkin-bank" {...props}></Icon>
<style>
:global(.d_4rlubza) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.125 32.444A9.75 9.75 0 1 1 24 24a9.75 9.75 0 1 0 4.875-8.443");
}

:global(.gdzi0w46r) {
  cx: 11px;
  cy: 20.869px;
  r: 0.75px;
  fill: currentColor;
}

:global(.l7okhcc4d) {
  cx: 30.5px;
  cy: 20.869px;
  r: 0.75px;
  fill: currentColor;
}

:global(.q9skithoe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.598 27.578c-2.144 1.522-4.553 1.522-6.697 0");
}

:global(.sswktgbuq) {
  cx: 37px;
  cy: 20.869px;
  r: 0.75px;
  fill: currentColor;
}

:global(.xdxzu4omp) {
  cx: 17.5px;
  cy: 20.869px;
  r: 0.75px;
  fill: currentColor;
}

:global(.yl647fboh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.099 27.578c-2.144 1.522-4.553 1.522-6.697 0");
}

</style>
