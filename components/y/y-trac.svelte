<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ggcwaserw"/><path class="erbm33b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:y-trac" {...props}></Icon>
<style>
:global(.erbm33b1r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.614 32.652l10.247-12.536l8.732 6.449l11.256-14.048");
}

:global(.ggcwaserw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.783 11.015v25.97h38.434");
}

</style>
