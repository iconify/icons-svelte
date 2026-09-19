<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xoaa3kbol"/><rect class="asflotbxb"/><rect class="xqmxtbcxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:widgets-by-you" {...props}></Icon>
<style>
:global(.asflotbxb) {
  width: 16px;
  height: 24px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.xoaa3kbol) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.444a4 4 0 0 0 0-8h-29a4 4 0 0 0 0 8z");
}

:global(.xqmxtbcxi) {
  width: 16px;
  height: 24px;
  x: 26.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
