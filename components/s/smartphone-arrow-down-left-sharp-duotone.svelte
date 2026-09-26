<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bwu_g5bwh"/><path class="gs7aj0bka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone-arrow-down-left-sharp-duotone" {...props}></Icon>
<style>
:global(.bwu_g5bwh) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 1L19 1C19.5523 1 20 1.4477 20 2L20 13L10 13L10 23L5 23C4.4477 23 4 22.5523 4 22L4 2C4 1.4477 4.4477 1 5 1Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.gs7aj0bka) {
  d: path("M14.5 6L9.5 6M13.1464 21.8536L18.2929 16.7071M13 15L13 22L20 22");
}

</style>
