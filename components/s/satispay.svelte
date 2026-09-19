<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bo9_pgbdj"/><path class="gn7dsqztd"/><path class="o6scgm7nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:satispay" {...props}></Icon>
<style>
:global(.bo9_pgbdj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 37.8L3.2 24l13.9-13.8");
}

:global(.gn7dsqztd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.3 24L11.8 4.5h13.5L44.8 24L25.3 43.5h0h-13.5z");
}

:global(.o6scgm7nb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.8 31.1L16.7 24l7.1-7.1m1.5-12.4h12.3l-6 6m0 27l6 6H25.3");
}

</style>
