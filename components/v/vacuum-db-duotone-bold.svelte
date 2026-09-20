<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqn8oeb4o"/><path class="nu0ti3ggl"/><path class="jycpvgb1i"/><path class="vmp8eebwz"/><path class="ohadvob9k"/><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="t0-mwc0xy"/><path class="o3x_gzblq"/><path class="qik8460ao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vacuum-db-duotone-bold" {...props}></Icon>
<style>
:global(.aqn8oeb4o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jycpvgb1i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.nu0ti3ggl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o3x_gzblq) {
  d: path("m8 13 4 4 4 -4");
}

:global(.ohadvob9k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 21h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qik8460ao) {
  d: path("M5 21h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.vmp8eebwz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 13 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
