<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w-0fmjjrl"/><path class="l7ws43byj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:screwdriver-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.l7ws43byj) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 16l7-7l4 4l-7 7a2.828 2.828 0 1 1-4-4m9-5l7-7");
}

:global(.w-0fmjjrl) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.293 8.293a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414l-7 7a3.828 3.828 0 0 1-5.414-5.414Z");
}

</style>
