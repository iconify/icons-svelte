<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="vdgw_si7l"/><path class="pm55nub4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:spaceplan" {...props}></Icon>
<style>
:global(.pm55nub4z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h6.158v6.158H5.5zm10.164 11.863l1.699-1.699");
}

:global(.vdgw_si7l) {
  cx: 25.745px;
  cy: 25.745px;
  r: 16.755px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
