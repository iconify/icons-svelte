<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="obd33rtth"/><path class="i_1zgffhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:software-update" {...props}></Icon>
<style>
:global(.i_1zgffhd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.922 20.142l-5.46-5.178l-5.458 5.178");
}

:global(.obd33rtth) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.401 4h18.124a3.01 3.01 0 0 1 3.02 3v33c0 1.657-1.352 3-3.02 3H15.4a3.01 3.01 0 0 1-3.02-3V7c0-1.657 1.352-3 3.02-3m9.063 26.272V14.964");
}

</style>
