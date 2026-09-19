<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="d0msigb4e"/><circle class="lnwe-jbao"/><circle class="qnez8j6zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:simplii" {...props}></Icon>
<style>
:global(.d0msigb4e) {
  cx: 8.5px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lnwe-jbao) {
  cx: 29.167px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qnez8j6zw) {
  cx: 39.5px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
