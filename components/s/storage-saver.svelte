<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yzqfrub6s"/><path class="r7msw9mbv"/><path class="uqllnzi_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:storage-saver" {...props}></Icon>
<style>
:global(.r7msw9mbv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.25 37.448v2.828a2.225 2.225 0 0 1-2.225 2.224h-26.05a2.225 2.225 0 0 1-2.224-2.224V10.297c0-1.228.996-2.224 2.224-2.224h2.781M25.31 5.5v6.221M19.533 5.5v6.221M13.756 5.5v6.221");
}

:global(.uqllnzi_v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.103 26.077l-6.35-6.35l-6.35 6.35");
}

:global(.yzqfrub6s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.31 8.073h3.084c1.18 0 2.312.468 3.146 1.303l6.406 6.406a4.45 4.45 0 0 1 1.303 3.146v11.244a2.225 2.225 0 0 1-2.224 2.224H24.977a2.225 2.225 0 0 1-2.224-2.224V24.54");
}

</style>
