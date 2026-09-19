<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e__u04y0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:squarehome2" {...props}></Icon>
<style>
:global(.e__u04y0p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h23v11h-23zm14 26h23v11h-23zm12-26h11v23h-11zm-26 14h11v23h-11z");
}

</style>
