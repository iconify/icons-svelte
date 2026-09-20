<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="myekf3bzc"/><path class="rrxso7m3p"/><path class="qnps6eb_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sibling-outline-regular" {...props}></Icon>
<style>
:global(.myekf3bzc) {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qnps6eb_y) {
  d: path("M4 19a8 8 0 0 1 16 0");
}

:global(.rrxso7m3p) {
  d: path("M14 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
