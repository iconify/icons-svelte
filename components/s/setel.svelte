<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mfvf950lk"/><path class="wl112cq5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:setel" {...props}></Icon>
<style>
:global(.mfvf950lk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.622L4.798 31.396h38.404zm19.202 28.774L24 45.377L4.798 31.396");
}

:global(.wl112cq5b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.594 31.392L24 45.378l-9.594-13.986L24 2.627z");
}

</style>
