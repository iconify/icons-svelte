<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xxobs597t"/><path class="nancp9ugm"/><path class="rgnpgnbjr"/><path class="fttf_kblh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:speech-recognize-outline-regular" {...props}></Icon>
<style>
:global(.fttf_kblh) {
  d: path("M16 14h5");
}

:global(.nancp9ugm) {
  d: path("M5.05 16.95a7 7 0 0 1 0 -9.9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rgnpgnbjr) {
  d: path("M16 10h5");
}

:global(.xxobs597t) {
  d: path("M7.88 14.12a3 3 0 0 1 0 -4.24");
}

</style>
