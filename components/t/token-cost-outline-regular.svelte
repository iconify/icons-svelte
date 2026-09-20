<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="guwflf-kp"/><path class="osjmvib6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:token-cost-outline-regular" {...props}></Icon>
<style>
:global(.guwflf-kp) {
  d: path("M4 5.5A2.5 2.5 0 0 1 6.5 3h11A2.5 2.5 0 0 1 20 5.5 2.5 2.5 0 0 1 17.5 8h-11A2.5 2.5 0 0 1 4 5.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.osjmvib6z) {
  d: path("M7 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
