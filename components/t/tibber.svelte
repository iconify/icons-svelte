<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n45nkj8_b"/><path class="k45ad7h6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tibber" {...props}></Icon>
<style>
:global(.k45ad7h6u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 30.324L22.419 43.5l15.284-22.662h-17.92");
}

:global(.n45nkj8_b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 17.676L25.581 4.5L10.297 27.162h17.92");
}

</style>
