<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="crf0mcbbl"/><path class="f9i8pu8tc"/><circle class="vg44ju7oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:yi-home" {...props}></Icon>
<style>
:global(.crf0mcbbl) {
  width: 22.115px;
  height: 32.823px;
  x: 12.988px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 11.057px;
}

:global(.f9i8pu8tc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.898 43.5h22.204");
}

:global(.vg44ju7oj) {
  cx: 24px;
  cy: 16.214px;
  r: 5.611px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
