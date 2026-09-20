<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ipkach1qn"/><path class="xslfg2evh"/><path class="axrnp4b4f"/><path class="fmr2g_bno"/><path class="yhgzmt2de"/><path class="yw_llwb7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:weather-station-outline-bold" {...props}></Icon>
<style>
:global(.axrnp4b4f) {
  d: path("M5 6h14");
}

:global(.fmr2g_bno) {
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ipkach1qn) {
  d: path("M12 6v15");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
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
