<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fo_662bai"/><path class="r3fzoobic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tandem" {...props}></Icon>
<style>
:global(.fo_662bai) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.313 11.813H43.5V24a12.19 12.19 0 0 1-12.187 12.188h0A12.19 12.19 0 0 1 19.124 24v0a12.19 12.19 0 0 1 12.188-12.187");
}

:global(.r3fzoobic) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.688 36.188H4.5h0V24a12.19 12.19 0 0 1 12.188-12.187h0A12.19 12.19 0 0 1 28.874 24h0a12.19 12.19 0 0 1-12.187 12.188");
}

</style>
