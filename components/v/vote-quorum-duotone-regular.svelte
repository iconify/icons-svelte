<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="znp-i32pq"/><path class="g8joi956b"/><path class="tatr9bssp"/><path class="rffs9ft4u"/><path class="h7k_twb0c"/><path class="lhz2jzbtp"/><path class="m_rvj96ky"/><path class="hi4ej1pvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vote-quorum-duotone-regular" {...props}></Icon>
<style>
:global(.g8joi956b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7k_twb0c) {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.hi4ej1pvu) {
  d: path("m9.5 11 2 2L15 9.5");
}

:global(.lhz2jzbtp) {
  d: path("M19.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.m_rvj96ky) {
  d: path("M13.27 15.28a3 3 0 1 1 -2.54 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rffs9ft4u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9.5 11 2 2L15 9.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tatr9bssp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.znp-i32pq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
