<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s79xpcu8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:uprock-earning" {...props}></Icon>
<style>
:global(.s79xpcu8h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.884 19.617L18.947 39.5h16.13L13.15 8.5h19.633c5.707 0 10.334 4.626 10.334 10.333S38.49 29.166 32.784 29.166h-5.016");
}

</style>
