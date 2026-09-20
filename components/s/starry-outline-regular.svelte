<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jl5_x8rdu"/><path class="lny_s1b9z"/><path class="ho29mccfb"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:starry-outline-regular" {...props}></Icon>
<style>
:global(.ho29mccfb) {
  d: path("m12 10.5 2.5 2.5 -2.5 2.5L9.5 13Z");
}

:global(.jl5_x8rdu) {
  d: path("m7 5 3 3 -3 3 -3 -3Z");
}

:global(.lny_s1b9z) {
  d: path("M16 3.5 18.5 6 16 8.5 13.5 6Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
