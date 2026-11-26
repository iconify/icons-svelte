<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qwkwe-b6h"/><path class="ut17vmb_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:stroke-line-join-round-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qwkwe-b6h) {
  stroke-opacity: 0.4;
  d: path("M11 22L11 11L22 11");
}

:global(.ut17vmb_f) {
  d: path("M3 22L3 11C3 6.5817 6.5817 3 11 3L22 3");
}

</style>
