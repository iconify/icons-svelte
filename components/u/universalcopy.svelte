<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s7bgdkb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:universalcopy" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s7bgdkb7o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.375 19.788h19.656m-19.656 5.989h11.832m2.608 3.189h2.67a2.67 2.67 0 0 1 2.67 2.67v0a2.67 2.67 0 0 1-2.67 2.67h0a2.67 2.67 0 0 1-2.67-2.67zm-16.951-6.294v2.67a2.67 2.67 0 0 1-2.67 2.67h0a2.67 2.67 0 0 1-2.67-2.67h0a2.67 2.67 0 0 1 2.67-2.67z");
}

</style>
