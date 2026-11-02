<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tv4vg2bhr"/><path class="dctk2rj5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ungroup-duocolor-sharp" {...props}></Icon>
<style>
:global(.dctk2rj5c) {
  d: path("M5 5h7v5H5z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tv4vg2bhr) {
  stroke-opacity: 0.4;
  d: path("M12 14h7v5h-7z");
}

</style>
