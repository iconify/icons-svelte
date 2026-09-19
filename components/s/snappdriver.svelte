<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="spozitbti"/><path class="mzqvfibph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:snappdriver" {...props}></Icon>
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

:global(.mzqvfibph) {
  d: path("m31.435 7.759l-3.868 14.67c-.927 3.517-1.501 6.386-5.181 6.421l-3.598.034l5.66-21.119z");
}

:global(.spozitbti) {
  cx: 21.211px;
  cy: 36.036px;
  r: 4.251px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
