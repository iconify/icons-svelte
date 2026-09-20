<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="ef4b-rb-i"/><path class="w4x83gbcm"/><path class="w3hnpdk3b"/><path class="frc90pbsi"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="a5uqb5btg"/><path class="qn21uclav"/><path class="mcdduacou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:threshold-line-duotone-regular" {...props}></Icon>
<style>
:global(.a5uqb5btg) {
  d: path("M9 14v4");
}

:global(.e_6o-gbms) {
  d: path("M6 10h13");
}

:global(.ef4b-rb-i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.frc90pbsi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mcdduacou) {
  d: path("M17 7v11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qn21uclav) {
  d: path("M13 12v6");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.w3hnpdk3b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w4x83gbcm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
