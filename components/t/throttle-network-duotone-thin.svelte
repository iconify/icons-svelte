<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="st_mp7wyv"/><path class="oqv9_8b1v"/><path class="ert_saboi"/><path class="sslmt1fkf"/><path class="u58l6cc7h"/><path class="f1vpicczb"/><path class="o0-3vqblf"/><path class="jcxg2bbvb"/><path class="e-p0c9bfw"/><path class="jlfl_ccwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:throttle-network-duotone-thin" {...props}></Icon>
<style>
:global(.e-p0c9bfw) {
  d: path("m8 3 6 6v6l-6 6");
}

:global(.ert_saboi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f1vpicczb) {
  d: path("M2 4h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.jlfl_ccwj) {
  d: path("M14 12h8");
}

:global(.o0-3vqblf) {
  d: path("M2 8h8");
}

:global(.oqv9_8b1v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sslmt1fkf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 3 6 6v6l-6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.st_mp7wyv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 4h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u58l6cc7h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
