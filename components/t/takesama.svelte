<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="gst3f0bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:takesama" {...props}></Icon>
<style>
:global(.gst3f0bff) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.776 19.427c-5.604 0-6.888-4.153-6.888-7.153c0 3-1.284 7.153-6.888 7.153s-6.887-4.153-6.887-7.153c0 3-1.285 7.153-6.888 7.153m6.887 4.364v3.9m13.776-3.9v3.9m-.579 5.167c-3.788 2.411-8.83 2.411-12.619 0");
}

:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
