<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwjllcbqv"/><path class="vtt-aac3x"/><path class="t511ecujx"/><path class="ck_r08b8b"/><path class="o0arf079a"/><path class="xbgca8j8q"/><path class="ipkach1qn"/><path class="xslfg2evh"/><path class="axrnp4b4f"/><path class="fmr2g_bno"/><path class="yhgzmt2de"/><path class="yw_llwb7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:weather-station-duotone-thin" {...props}></Icon>
<style>
:global(.axrnp4b4f) {
  d: path("M5 6h14");
}

:global(.ck_r08b8b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fmr2g_bno) {
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gwjllcbqv) {
  fill: currentColor;
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.ipkach1qn) {
  d: path("M12 6v15");
}

:global(.o0arf079a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t511ecujx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vtt-aac3x) {
  fill: currentColor;
  d: path("M17 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xbgca8j8q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h6v4h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

:global(.yhgzmt2de) {
  d: path("M17 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yw_llwb7j) {
  d: path("M12 12h6v4h-6");
}

</style>
