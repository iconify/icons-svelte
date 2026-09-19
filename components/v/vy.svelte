<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="g1k9f6bqt"/><path class="rp8hb0v4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vy" {...props}></Icon>
<style>
:global(.g1k9f6bqt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.67 15.546l-5.431 16.806L12.5 15.546m23 6.968v5.739c0 2.357-1.947 4.202-4.202 4.202h0c-1.23 0-2.357-.41-2.971-1.23");
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.rp8hb0v4g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.5 15.546v6.968c0 2.357-1.947 4.202-4.202 4.202h0c-2.357 0-4.201-1.947-4.201-4.202v-6.969");
}

</style>
