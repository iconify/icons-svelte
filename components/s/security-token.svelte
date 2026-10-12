<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bug-6v0yw"/><path class="owwru7bmc"/><rect class="j5nsipxpg"/><path class="rr3d11bni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:security-token" {...props}></Icon>
<style>
:global(.bug-6v0yw) {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  rx: 3.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j5nsipxpg) {
  width: 5.5px;
  height: 6px;
  x: 9.25px;
  y: 11.75px;
  rx: 1.25px;
}

:global(.owwru7bmc) {
  d: path("M12 5.75a1.5 1.5 0 1 1 0 3a1.5 1.5 0 1 1 0-3");
}

:global(.rr3d11bni) {
  d: path("M10.75 14.75h.75m1 0h.75");
}

</style>
