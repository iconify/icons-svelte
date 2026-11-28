<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y03nb23xy"/><path clip-rule="evenodd" class="yfe6o_b9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:serial-port-off-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y03nb23xy) {
  d: path("M18 18H4.159L2.002 6H6M10.657 6H21.999L20.246 15.75M1.707 1.707L22.293 22.293");
}

:global(.yfe6o_b9o) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 10C17 10.552 16.552 11 16 11C15.448 11 15 10.552 15 10C15 9.448 15.448 9 16 9C16.552 9 17 9.448 17 10Z");
  stroke: none;
}

</style>
