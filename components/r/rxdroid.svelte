<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="sbuhdtbfx"/><path class="s2d7v5oci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rxdroid" {...props}></Icon>
<style>
:global(.s2d7v5oci) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.111 31.111L16.889 16.889");
}

:global(.sbuhdtbfx) {
  width: 43.995px;
  height: 20.112px;
  x: 2.002px;
  y: 13.944px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.056px;
}

</style>
