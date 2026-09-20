<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyks9vbfn"/><path class="dpvrwwhil"/><path class="i00vfab_y"/><path class="zrqurcb-a"/><path class="g3eaxfafx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scorecard-outline-regular" {...props}></Icon>
<style>
:global(.dpvrwwhil) {
  d: path("M5 9h8");
}

:global(.g3eaxfafx) {
  d: path("m15 15 2 2 3 -3");
}

:global(.i00vfab_y) {
  d: path("m15 9 2 2 3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vyks9vbfn) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.zrqurcb-a) {
  d: path("M5 15h8");
}

</style>
