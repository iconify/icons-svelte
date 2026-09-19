<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="egd59tb2y"/><path class="bgey4_chq"/><path class="zglj4-1vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:volkswagen" {...props}></Icon>
<style>
:global(.bgey4_chq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.297 16.894L31.51 40.74L24 25.386L16.49 40.74L3.703 16.894");
}

:global(.egd59tb2y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.876 0 21.5 9.624 21.5 21.5S35.876 45.5 24 45.5S2.5 35.876 2.5 24S12.124 2.5 24 2.5");
}

:global(.zglj4-1vi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.825 4.39L24 22.47L15.174 4.39");
}

</style>
