<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vvpdnhx8w"/><path class="hiem7gb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:useeum" {...props}></Icon>
<style>
:global(.hiem7gb3w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5V24c0 10.217 8.283 18.5 18.5 18.5S42.5 34.217 42.5 24V5.5");
}

:global(.vvpdnhx8w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 5.5V24c0 5.238 4.262 9.5 9.5 9.5s9.5-4.262 9.5-9.5V5.5");
}

</style>
