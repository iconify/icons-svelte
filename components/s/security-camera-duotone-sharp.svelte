<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u0q99nbyu"/><path class="z7u980b5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:security-camera-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.u0q99nbyu) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m18.692 3.066l2.071 7.727l-15.455 4.141l-2.071-7.727Z");
}

:global(.z7u980b5i) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3.237 7.207l15.455-4.141l2.07 7.727l-15.454 4.141ZM12 13.14V17h7m0-1v5M15.605 6.999l.518 1.932");
}

</style>
