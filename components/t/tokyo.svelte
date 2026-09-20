<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hyb_4pkwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tokyo" {...props}></Icon>
<style>
:global(.hyb_4pkwa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5C24 33.626 14.374 24 2.5 24C2.5 12.126 12.126 2.5 24 2.5S45.5 12.126 45.5 24C33.626 24 24 33.626 24 45.5");
}

</style>
