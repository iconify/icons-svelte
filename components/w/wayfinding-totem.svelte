<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gmwpzbbwt"/><path class="bn1axxb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wayfinding-totem" {...props}></Icon>
<style>
:global(.bn1axxb9f) {
  d: path("M9.5 7h5M13 5.5L14.5 7L13 8.5m1.5 5h-5M11 12l-1.5 1.5L11 15");
}

:global(.gmwpzbbwt) {
  d: path("M9.125 2.5h5.75A2.625 2.625 0 0 1 17.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 6.5 18.875V5.125A2.625 2.625 0 0 1 9.125 2.5M3.5 21.5h17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
