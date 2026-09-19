<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hgqn3mblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:stockx" {...props}></Icon>
<style>
:global(.hgqn3mblu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.599 39.44L42.5 8.168M27.255 26.821L42.5 39.831M20.17 20.775L5.5 8.257");
}

</style>
