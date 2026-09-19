<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihkt6zigk"/><path class="u-aul108h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:timelimit" {...props}></Icon>
<style>
:global(.ihkt6zigk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.14 24L9 32.24a16.37 16.37 0 1 0 14.14-24.6Z");
}

:global(.u-aul108h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5A21.5 21.5 0 1 1 45.5 24A21.51 21.51 0 0 1 24 45.5");
}

</style>
