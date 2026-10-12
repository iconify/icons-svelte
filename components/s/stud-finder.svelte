<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ys03ey_3q"/><path class="t2zvjcbsg"/><path class="rhj7-w4rz"/><path class="p_opui6bf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stud-finder" {...props}></Icon>
<style>
:global(.p_opui6bf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.17 6.67a4 4 0 0 1 5.66 0m-7.6-1.94a6.75 6.75 0 0 1 9.54 0");
}

:global(.rhj7-w4rz) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.5h.01");
}

:global(.t2zvjcbsg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 13.25h6.5v2.5h-6.5Z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ys03ey_3q) {
  width: 13.5px;
  height: 11.25px;
  x: 5.25px;
  y: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

</style>
