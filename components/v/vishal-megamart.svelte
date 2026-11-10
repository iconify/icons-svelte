<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p4vhc2_6q"/><path class="q1cq2tbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vishal-megamart" {...props}></Icon>
<style>
:global(.p4vhc2_6q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.605 9.764h9.254L24.214 42.5L6.14 9.764h9.682l8.136 15.254z");
}

:global(.q1cq2tbjy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.377 5.5L23.96 19L16.623 5.5z");
}

</style>
