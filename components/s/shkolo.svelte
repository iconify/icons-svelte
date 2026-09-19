<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k2yns9eam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shkolo" {...props}></Icon>
<style>
:global(.k2yns9eam) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 35H38a5.5 5.5 0 0 0 5.5-5.5h0A5.5 5.5 0 0 0 38 24H10a5.5 5.5 0 0 1-5.5-5.5h0A5.5 5.5 0 0 1 10 13h32.5");
}

</style>
