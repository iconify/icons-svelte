<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tqi02e-jv"/><path class="gwt_wbb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:seriesguide" {...props}></Icon>
<style>
:global(.gwt_wbb2t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 10.5h-31a4 4 0 0 0-4 4v19a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4v-19a4 4 0 0 0-4-4");
}

:global(.tqi02e-jv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.001 16.872L20.36 31.513s-7.243-7.175-7.32-7.175");
}

</style>
