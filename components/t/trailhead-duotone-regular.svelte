<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjb6iab1i"/><path class="dfk6racie"/><path class="lbkuffism"/><path class="ftqzjnb8u"/><path class="naxi-2ilz"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trailhead-duotone-regular" {...props}></Icon>
<style>
:global(.dfk6racie) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 5h10l3.5 3.5L16 12H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.lbkuffism) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.naxi-2ilz) {
  d: path("M6 5h10l3.5 3.5L16 12H6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.rjb6iab1i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
