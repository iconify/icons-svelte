<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w1te0zbhr"/><path class="pxx9lsmau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:security-camera-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pxx9lsmau) {
  d: path("m3.237 7.207l15.455-4.141l2.07 7.727l-15.454 4.141ZM12 13.14V17h7m0-1v5");
}

:global(.w1te0zbhr) {
  stroke-opacity: 0.4;
  d: path("m15.605 6.999l.518 1.932");
}

</style>
