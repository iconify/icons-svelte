<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s4o090mfm"/><path class="qf99stm5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tarot-stars" {...props}></Icon>
<style>
:global(.qf99stm5x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5L45.5 24L24 45.5L2.5 24z");
}

:global(.s4o090mfm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.405 8.405h31.19v31.19H8.405z");
}

</style>
