<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lsng_0odv"/><path class="ic8i7sb2b"/><path class="z9adew4xp"/><path class="emzb-0-_j"/><path class="adxensbci"/><path class="yzggow1fx"/><path class="e0q5_ylwf"/><path class="ux-gk6uae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tiered-reward-duotone-regular" {...props}></Icon>
<style>
:global(.adxensbci) {
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
}

:global(.e0q5_ylwf) {
  d: path("M12 6.5V11");
}

:global(.emzb-0-_j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 5v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ic8i7sb2b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lsng_0odv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ux-gk6uae) {
  d: path("M15 5v6");
}

:global(.yzggow1fx) {
  d: path("M9 8v3");
}

:global(.z9adew4xp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6.5V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
