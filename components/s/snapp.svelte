<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="lt67sibvn"/><path class="xh6aspbnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:snapp" {...props}></Icon>
<style>
:global(.lt67sibvn) {
  cx: 20.419px;
  cy: 38.403px;
  r: 5.097px;
}

:global(.xh6aspbnw) {
  d: path("M32.678 4.5L28.04 22.089c-1.111 4.217-1.8 7.656-6.212 7.698l-4.314.041L24.3 4.508z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
