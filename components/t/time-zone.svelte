<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x_25ybdoh"/><path class="cspxfp4ro"/><path class="v7xutcx-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:time-zone" {...props}></Icon>
<style>
:global(.cspxfp4ro) {
  d: path("M12 2.5C9.5 5 8 8.5 8 12s1.5 7 4 9.5m0-19c2.5 2.5 4 6 4 9.5m-1 6.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v7xutcx-f) {
  d: path("M18 17v1.25l1 .5");
}

:global(.x_25ybdoh) {
  d: path("M12 21.5a9.5 9.5 0 1 1 9.5-9.5m-19 0h19");
}

</style>
