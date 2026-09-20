<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wt9oil39f"/><path class="ni7913pru"/><path class="mu-p7sbhe"/><path class="qm17m3bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:speech-synth-outline-regular" {...props}></Icon>
<style>
:global(.mu-p7sbhe) {
  d: path("M16.12 9.88a3 3 0 0 1 0 4.24");
}

:global(.ni7913pru) {
  d: path("M3 14h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qm17m3bad) {
  d: path("M18.95 7.05a7 7 0 0 1 0 9.9");
}

:global(.wt9oil39f) {
  d: path("M3 10h5");
}

</style>
