<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lsng_0odv"/><path class="g0jrpiwaf"/><path class="adxensbci"/><path class="nmwlt6bbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:staff-pick-duotone-regular" {...props}></Icon>
<style>
:global(.adxensbci) {
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
}

:global(.g0jrpiwaf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 8.5 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lsng_0odv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nmwlt6bbh) {
  d: path("m9 8.5 2 2 4 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
