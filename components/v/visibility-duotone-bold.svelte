<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="e41rtzbhm"/><path class="xaz90clio"/><path class="m7hcxw29t"/><path class="k1tyfwlxi"/><path class="rp243mbkd"/><path class="bo51iypxr"/><path class="rkhcgsbdl"/><path class="irm-6r_xs"/><path class="uzi41e83o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:visibility-duotone-bold" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e41rtzbhm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.irm-6r_xs) {
  d: path("M3 17v4");
}

:global(.k1tyfwlxi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m7hcxw29t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.rp243mbkd) {
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uzi41e83o) {
  d: path("M21 17v4");
}

:global(.xaz90clio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
