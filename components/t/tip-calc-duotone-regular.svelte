<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g7d56fjnv"/><path class="njx-i5bnu"/><path class="a_0xpnjsq"/><path class="vyks9vbfn"/><path class="ogtwkzbca"/><path class="eahy924ne"/><path class="zjleuacmi"/><path class="lxoo1ac9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tip-calc-duotone-regular" {...props}></Icon>
<style>
:global(.a_0xpnjsq) {
  fill: currentColor;
  d: path("M10 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.eahy924ne) {
  d: path("M6 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.g7d56fjnv) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lxoo1ac9h) {
  d: path("M10 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.njx-i5bnu) {
  fill: currentColor;
  d: path("M6 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ogtwkzbca) {
  d: path("M22 9.5h-7v5h7");
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.zjleuacmi) {
  d: path("m6.5 14.5 5 -5");
}

</style>
