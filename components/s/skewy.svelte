<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="pth7gz5zl"/><path class="ycp8c6tcz"/><path class="q7kxhd7zd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:skewy" {...props}></Icon>
<style>
:global(.pth7gz5zl) {
  width: 7.575px;
  height: 11.435px;
  x: 27.027px;
  y: 28.82px;
  rx: 3.788px;
  ry: 3.788px;
}

:global(.q7kxhd7zd) {
  d: path("M6.54 30.439a17.1 17.1 0 0 1-.814-5.21c0-9.746 8.179-17.648 18.269-17.648h0c10.089 0 18.268 7.902 18.268 17.649h0c0 1.761-.273 3.513-.81 5.197");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ycp8c6tcz) {
  d: path("M14.832 40.254V28.82l7.575 11.434V28.82M9.42 40.37c-2.368-1.022-3.92-3.486-3.92-6.226s1.552-5.205 3.92-6.226m29.04-.05c2.431.987 4.04 3.486 4.04 6.276h0c0 2.79-1.609 5.289-4.04 6.275");
}

</style>
