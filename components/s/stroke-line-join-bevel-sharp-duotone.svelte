<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qwkwe-b6h"/><path class="l6m8bo8hf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:stroke-line-join-bevel-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.l6m8bo8hf) {
  d: path("M3 22L3 11L11 3L22 3");
}

:global(.qwkwe-b6h) {
  stroke-opacity: 0.4;
  d: path("M11 22L11 11L22 11");
}

</style>
