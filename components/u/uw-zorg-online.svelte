<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d15k6ob9j"/><path class="tlsbkt65n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:uw-zorg-online" {...props}></Icon>
<style>
:global(.d15k6ob9j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 18H30v-6.5c0-3.3-2.7-6-6-6s-6 2.7-6 6V18h-6.5c-3.3 0-6 2.7-6 6s2.7 6 6 6H18v6.5c0 3.3 2.7 6 6 6s6-2.7 6-6V30h6.5c3.3 0 6-2.7 6-6s-2.7-6-6-6");
}

:global(.tlsbkt65n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 18c-6.627 0-12 5.373-12 12");
}

</style>
