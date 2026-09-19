<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hfrmw-b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:txd-tool" {...props}></Icon>
<style>
:global(.hfrmw-b_u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 21.757l6.366 6.373l7.955-7.965l7.956 7.965l7.956-7.965l6.767 6.767M10.158 5.5h27.685a4.647 4.647 0 0 1 4.657 4.637v27.705a4.647 4.647 0 0 1-4.636 4.658H10.158A4.647 4.647 0 0 1 5.5 37.864V10.157A4.647 4.647 0 0 1 10.137 5.5z");
}

</style>
