<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t1rg4fbhf"/><path class="fhc_6lohv"/><path class="eep6j8bvo"/><path class="lvewu-bzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:step-back-outline-regular" {...props}></Icon>
<style>
:global(.eep6j8bvo) {
  d: path("M11 8a4 4 0 1 1 4 4");
}

:global(.fhc_6lohv) {
  d: path("M4.5 9.5 2 12l2.5 2.5");
}

:global(.lvewu-bzn) {
  d: path("M14 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t1rg4fbhf) {
  d: path("M3 12h5");
}

</style>
