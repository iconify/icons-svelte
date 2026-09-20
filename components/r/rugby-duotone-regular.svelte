<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ib5f7qtct"/><path class="epka50bri"/><path class="f2vh026ub"/><path class="y0y0ccsoe"/><path class="fkf_gcbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rugby-duotone-regular" {...props}></Icon>
<style>
:global(.epka50bri) {
  d: path("M3 12c3 -4 6 -7 9 -7s6 3 9 7c-3 4 -6 7 -9 7s-6 -3 -9 -7");
}

:global(.f2vh026ub) {
  d: path("M10 9h4");
}

:global(.fkf_gcbra) {
  d: path("M10 15h4");
}

:global(.ib5f7qtct) {
  fill: currentColor;
  d: path("M3 12c3 -4 6 -7 9 -7s6 3 9 7c-3 4 -6 7 -9 7s-6 -3 -9 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

</style>
