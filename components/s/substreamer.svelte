<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qe9gkb-zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:substreamer" {...props}></Icon>
<style>
:global(.qe9gkb-zf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 9v30M9.375 15.207v17.586m9.75-17.586v17.586M4.5 20.897v6.206M33.75 9v30m-4.875-23.793v17.586m9.75-17.586v17.586M24 20.897v6.206m19.5-6.206v6.206");
}

</style>
