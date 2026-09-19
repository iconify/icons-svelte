<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9o9p58vv"/><path class="mzhozrb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:talking-points" {...props}></Icon>
<style>
:global(.i9o9p58vv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.765 20.623v-3.16L35.6 20.265H25.217c-3.135 0-5.7 2.565-5.7 5.7v8.123c0 3.134 2.565 5.7 5.7 5.7H37.8c3.135 0 5.7-2.565 5.7-5.7v-8.123c0-2.444-1.562-4.536-3.735-5.342");
}

:global(.mzhozrb9a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.235 27.377v3.16l4.165-2.802h10.383c3.135 0 5.7-2.565 5.7-5.7v-8.122c0-3.135-2.565-5.7-5.7-5.7H10.2c-3.135 0-5.7 2.565-5.7 5.7v8.122c0 2.444 1.562 4.536 3.735 5.342");
}

</style>
