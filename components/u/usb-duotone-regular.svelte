<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cvlwadsxk"/><path class="hsnod820c"/><path class="hheigfx4d"/><path class="m_6avib3e"/><path class="ib0uz7xmw"/><path class="jhjyblmry"/><path class="g2aaxgb5s"/><path class="exre5jj_d"/><path class="b9e7op5tz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:usb-duotone-regular" {...props}></Icon>
<style>
:global(.b9e7op5tz) {
  d: path("M3 7.5h4.5V12H3Z");
}

:global(.cvlwadsxk) {
  fill: currentColor;
  d: path("M10 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.exre5jj_d) {
  d: path("m12 15 -4.5 -4.5");
}

:global(.g2aaxgb5s) {
  d: path("M15.5 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hheigfx4d) {
  fill: currentColor;
  d: path("M3 7.5h4.5V12H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hsnod820c) {
  fill: currentColor;
  d: path("M15.5 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ib0uz7xmw) {
  d: path("M10 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jhjyblmry) {
  d: path("m12 12 4.5 -4.5");
}

:global(.m_6avib3e) {
  d: path("M12 3v17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
