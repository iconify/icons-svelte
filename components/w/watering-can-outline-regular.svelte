<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dwnj8ebpv"/><path class="kkard_6ho"/><path class="lm2p_gfvh"/><path class="j6kp_yter"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:watering-can-outline-regular" {...props}></Icon>
<style>
:global(.dwnj8ebpv) {
  d: path("M6 10v10h10V10Z");
}

:global(.j6kp_yter) {
  d: path("M8 10c0 -4 6 -4 6 0");
}

:global(.kkard_6ho) {
  d: path("m16 12 5 -5");
}

:global(.lm2p_gfvh) {
  d: path("m19 5 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
