<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hjdsycb3x"/><path class="z96vn00py"/><path class="y60rjib_g"/><path class="fvc8noqew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:run-distance-duotone-regular" {...props}></Icon>
<style>
:global(.fvc8noqew) {
  d: path("M16 3h4v4h-4");
}

:global(.hjdsycb3x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 21 5 -5v-4l5 -5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y60rjib_g) {
  d: path("m2 21 5 -5v-4l5 -5h4");
}

:global(.z96vn00py) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 3h4v4h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
