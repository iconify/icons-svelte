<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fqvaanbwm"/><path class="lwmow_bne"/><path class="uogqi4bmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:water-quality-duotone-thin" {...props}></Icon>
<style>
:global(.fqvaanbwm) {
  fill: currentColor;
  d: path("m12 4 8 8a8 8 0 0 1 -16 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lwmow_bne) {
  d: path("m12 4 8 8a8 8 0 0 1 -16 0Z");
}

:global(.uogqi4bmc) {
  d: path("m8 13 3 3 5 -5");
}

</style>
