<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oaqnt5b7k"/><path class="hcndpabaq"/><path class="y60rjib_g"/><path class="fvc8noqew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:run-distance-duotone-thin" {...props}></Icon>
<style>
:global(.fvc8noqew) {
  d: path("M16 3h4v4h-4");
}

:global(.hcndpabaq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 3h4v4h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oaqnt5b7k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 21 5 -5v-4l5 -5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y60rjib_g) {
  d: path("m2 21 5 -5v-4l5 -5h4");
}

</style>
