<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bn5v7b2yw"/><path class="j1d59w99t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:stay-hydrated" {...props}></Icon>
<style>
:global(.bn5v7b2yw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 30.5c0-12.011-13-26-13-26s-13 13.989-13 26a13 13 0 0 0 26 0m-13 .565V20.916m6.43 10.149H24");
}

:global(.j1d59w99t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.518 30.378A9.48 9.48 0 0 0 24 39.86");
}

</style>
