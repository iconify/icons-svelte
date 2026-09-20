<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o0u5m7z1w"/><path class="y-n_bmb1w"/><path class="jpz_xcbiq"/><path class="c9h3x0bhp"/><path class="bt_2bvgpa"/><path class="g_eatebwd"/><path class="kx8w1xsla"/><path class="hf-3i5bym"/><path class="jnbv45bnp"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:team-people-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c9h3x0bhp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g_eatebwd) {
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hf-3i5bym) {
  d: path("M15 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jnbv45bnp) {
  d: path("M14 14a3 3 0 0 1 6 0");
}

:global(.jpz_xcbiq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kx8w1xsla) {
  d: path("M4 14a3 3 0 0 1 6 0");
}

:global(.o0u5m7z1w) {
  fill: currentColor;
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.y-n_bmb1w) {
  fill: currentColor;
  d: path("M15 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
