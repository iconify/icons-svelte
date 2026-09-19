<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="dws-4ubsa"/><circle class="emejqxv9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tui-poland" {...props}></Icon>
<style>
:global(.dws-4ubsa) {
  d: path("m5.5 20.975l11.068.11m-5.326.392s1.966 15.276 11.294 15.782s13.402-12.301 13.402-12.301");
}

:global(.emejqxv9s) {
  cx: 39.06px;
  cy: 14.166px;
  r: 3.44px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
