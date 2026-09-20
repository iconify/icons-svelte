<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="s9jzbjbwv"/><path class="enu3nubgv"/><path class="z8yjphbma"/><path class="cupnz1b-s"/><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="t0-mwc0xy"/><path class="o3x_gzblq"/><path class="qik8460ao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vacuum-db-duotone-thin" {...props}></Icon>
<style>
:global(.cupnz1b-s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 21h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.enu3nubgv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.o3x_gzblq) {
  d: path("m8 13 4 4 4 -4");
}

:global(.qik8460ao) {
  d: path("M5 21h14");
}

:global(.r0_oskb4z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s9jzbjbwv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.z8yjphbma) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 13 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
