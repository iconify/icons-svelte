<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lnkmmebvu"/><path class="kojzey_1u"/><path class="hzfx__bqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:table-tennis-outline-regular" {...props}></Icon>
<style>
:global(.hzfx__bqu) {
  d: path("M18 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kojzey_1u) {
  d: path("M10 17v4");
}

:global(.lnkmmebvu) {
  d: path("M3 10a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
