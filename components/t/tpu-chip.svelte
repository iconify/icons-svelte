<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="k1eobnb6q"/><path class="pysxzsoqm"/><path class="gye4zw_nr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tpu-chip" {...props}></Icon>
<style>
:global(.gye4zw_nr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.75v3m3.25-3v3m3.25-3v3m-6.5 12.5v3m3.25-3v3m3.25-3v3M2.75 8.75h3m-3 3.25h3m-3 3.25h3m12.5-6.5h3m-3 3.25h3m-3 3.25h3");
}

:global(.k1eobnb6q) {
  width: 12.5px;
  height: 12.5px;
  x: 5.75px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.pysxzsoqm) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 8.75h.01m3.24 0h.01m3.24 0h.01M8.75 12h.01M12 12h.01m3.24 0h.01m-6.51 3.25h.01m3.24 0h.01m3.24 0h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
