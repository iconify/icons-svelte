<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ujvpm-bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tsumugino" {...props}></Icon>
<style>
:global(.ujvpm-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24H14m5 0h10m5 0h11.5M3.85 16.5h40.3m-40.3 15H21.5m5 0h17.65M24 2.5V14m0 5v2.5m0 5v19m7.5-41.65V14m0 5v10m0 5v10.15m-15-40.3V14m0 5v10m0 5v10.15");
}

</style>
