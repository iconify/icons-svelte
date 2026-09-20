<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y60rjib_g"/><path class="fvc8noqew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:run-distance-outline-regular" {...props}></Icon>
<style>
:global(.fvc8noqew) {
  d: path("M16 3h4v4h-4");
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

</style>
