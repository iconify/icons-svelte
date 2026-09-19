<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uj8mev2_w"/><circle class="g1exsibbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:veryfit" {...props}></Icon>
<style>
:global(.g1exsibbv) {
  cx: 40.5px;
  cy: 22.466px;
  r: 0.75px;
  fill: currentColor;
}

:global(.uj8mev2_w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 9.5H27l-13.243 29L4.5 22.466h10.579m6 0H33.5");
}

</style>
