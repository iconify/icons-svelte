<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="on3tkl32s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:the-verge" {...props}></Icon>
<style>
:global(.on3tkl32s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 7.202h-7.17L21.605 40.798h7.17zM22.378 30.965L15.23 13.454h9.45V7.207H5.5l9.718 23.758z");
}

</style>
