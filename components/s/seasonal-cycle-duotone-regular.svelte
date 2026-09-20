<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="raue1-0hj"/><path class="aiqm6_pau"/><path class="h06k0cc0f"/><path class="oh3qc3kah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:seasonal-cycle-duotone-regular" {...props}></Icon>
<style>
:global(.aiqm6_pau) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 12a4 4 0 0 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h06k0cc0f) {
  d: path("M3 12a4 4 0 0 1 8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oh3qc3kah) {
  d: path("M19 12a4 4 0 0 1 -8 0");
}

:global(.raue1-0hj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
