<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b_5y93rik"/><path class="xucfzr8ng"/><path class="zy54a7bml"/><path class="i2-ny_bzf"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transit-gateway-outline-regular" {...props}></Icon>
<style>
:global(.b_5y93rik) {
  d: path("m12 8.5 3.5 3.5 -3.5 3.5L8.5 12Z");
}

:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xucfzr8ng) {
  d: path("M3 12h4");
}

:global(.zy54a7bml) {
  d: path("M17 12h4");
}

</style>
