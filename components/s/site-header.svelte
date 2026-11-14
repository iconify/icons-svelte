<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ugs6g_mvm"/><path class="z46iwr9jz"/><path class="zr08r8a0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:site-header" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ugs6g_mvm) {
  d: path("M7 2.5h10A3.5 3.5 0 0 1 20.5 6v12a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V6A3.5 3.5 0 0 1 7 2.5");
}

:global(.z46iwr9jz) {
  fill: currentColor;
  d: path("M3.5 8V4.5a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2V8Z");
}

:global(.zr08r8a0n) {
  d: path("M7 13h10M7 17h6");
}

</style>
