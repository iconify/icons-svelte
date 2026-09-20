<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="cspceacnq"/><path class="doxmgbcyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:semantic-outline-regular" {...props}></Icon>
<style>
:global(.cspceacnq) {
  d: path("m7 9 2.5 -2.5L12 9l2.5 -2.5L17 9");
}

:global(.doxmgbcyh) {
  d: path("m7 14 2.5 -2.5L12 14l2.5 -2.5L17 14");
}

:global(.hbdbg_bcy) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.lyjarcbwz) {
  d: path("M7 18v3l3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
