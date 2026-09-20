<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uxahocbdu"/><path class="iqvyq-b-p"/><path class="vw2katk9z"/><path class="gr1zxddav"/><path class="dpxa52b_o"/><path class="f018rabbl"/><path class="d8z8gbsnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunflower-duotone-thin" {...props}></Icon>
<style>
:global(.d8z8gbsnd) {
  d: path("M13 21c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.dpxa52b_o) {
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

:global(.f018rabbl) {
  d: path("M12 15.5V21");
}

:global(.gr1zxddav) {
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iqvyq-b-p) {
  fill: currentColor;
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uxahocbdu) {
  fill: currentColor;
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vw2katk9z) {
  fill: currentColor;
  d: path("M13 21c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
