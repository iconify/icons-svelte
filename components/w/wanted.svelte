<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nclauyb-k"/><path class="vrkdxcbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wanted" {...props}></Icon>
<style>
:global(.nclauyb-k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 24H37a6.5 6.5 0 1 1-6.5 6.5V11h-13v11");
}

:global(.vrkdxcbto) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.5 24h-24l13 13V26");
}

</style>
