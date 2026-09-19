<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="puw4vsb2c"/><path class="nmkl42bjm"/><path class="vo-78jbfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vivo-console" {...props}></Icon>
<style>
:global(.nmkl42bjm) {
  d: path("m24 39.59l-13.486-7.777V16.277");
}

:global(.puw4vsb2c) {
  d: path("M40.04 14.75v18.5L24 42.5L7.96 33.25v-18.5L24 5.5zm-32.08.086L24 23.901m0 .017l16.04-9.082M24 42.244V23.918");
}

:global(.vo-78jbfi) {
  d: path("m23.998 34.263l-8.934-5.153V18.85");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
