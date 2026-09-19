<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dszltm0hg"/><circle class="e2huf9b5y"/><circle class="p0xybwe4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:swappa" {...props}></Icon>
<style>
:global(.dszltm0hg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.93 32.043A21.457 21.457 0 0 0 27 2.733M7.079 37.234a21.452 21.452 0 0 0 33.842 0M21 2.733a21.457 21.457 0 0 0-16.93 29.31");
}

:global(.e2huf9b5y) {
  cx: 17.5px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.p0xybwe4v) {
  cx: 30.5px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
