<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="hpg4nyb0c"/><circle class="a9gih1brb"/><circle class="eqgttw32j"/><circle class="ch135fbgg"/><path class="cylfc9fqr"/><path class="sk71f0bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zhed" {...props}></Icon>
<style>
:global(.a9gih1brb) {
  cx: 8px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ch135fbgg) {
  cx: 24px;
  cy: 8px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.cylfc9fqr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 15.5h17v17h-17z");
}

:global(.eqgttw32j) {
  cx: 24px;
  cy: 40px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hpg4nyb0c) {
  cx: 40px;
  cy: 24px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sk71f0bnd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 20h7l-7 8h7");
}

</style>
