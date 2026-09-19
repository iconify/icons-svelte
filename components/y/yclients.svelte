<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lkr-voyuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:yclients" {...props}></Icon>
<style>
:global(.lkr-voyuy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.228 19.375L22.238 5.5H6.18zm-.89 10.792L27.578 5.5H41.82l-21.362 37z");
}

</style>
