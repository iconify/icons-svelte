<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nm6a4vb2m"/><path class="u-aul108h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vrnetarif" {...props}></Icon>
<style>
:global(.nm6a4vb2m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5a8.74 8.74 0 0 1-8.4-8.74v-5.68a8.74 8.74 0 0 1 8.74-8.75a8.74 8.74 0 0 1 8.74 8.75v2.84H15.6");
}

:global(.u-aul108h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5A21.5 21.5 0 1 1 45.5 24A21.51 21.51 0 0 1 24 45.5");
}

</style>
