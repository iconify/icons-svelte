<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9hyh8z2l"/><rect class="nsmcnccwu"/><rect class="rswldpbuf"/><path class="upl-ibc5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scaffolding" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nsmcnccwu) {
  width: 15px;
  height: 2.5px;
  x: 4.5px;
  y: 6.75px;
  rx: 0.5px;
}

:global(.rswldpbuf) {
  width: 15px;
  height: 2.5px;
  x: 4.5px;
  y: 13.75px;
  rx: 0.5px;
}

:global(.upl-ibc5f) {
  d: path("M9.5 16.25v5m5-5v5m-5-2.5h5m-5-9.5v4.5m5-4.5v4.5m-5-2.25h5");
}

:global(.z9hyh8z2l) {
  d: path("M4.5 2.75v18.5m15-18.5v18.5m-16.75 0h18.5M4.5 4.25h15");
}

</style>
