<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sqmravmye"/><path class="uxahocbdu"/><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="gr1zxddav"/><path class="rrzohjbez"/><path class="e5edzvbgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:secret-message-duotone-regular" {...props}></Icon>
<style>
:global(.e5edzvbgi) {
  d: path("M12 14h2.5");
}

:global(.gr1zxddav) {
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hbdbg_bcy) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.lyjarcbwz) {
  d: path("M7 18v3l3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rrzohjbez) {
  d: path("M12 12v3");
}

:global(.sqmravmye) {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uxahocbdu) {
  fill: currentColor;
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
