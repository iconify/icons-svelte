<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eyx95fmam"/><path class="jk87mm2cv"/><path class="lr02_ebwb"/><path class="h1s_avbod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:weather-hourly-outline-regular" {...props}></Icon>
<style>
:global(.eyx95fmam) {
  d: path("M4 16a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 7a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.h1s_avbod) {
  d: path("M17 19v3");
}

:global(.jk87mm2cv) {
  d: path("M7 19v3");
}

:global(.lr02_ebwb) {
  d: path("M12 19v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
