<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lny_l6bpa"/><path class="ky2prbbwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:step-into-duocolor" {...props}></Icon>
<style>
:global(.ky2prbbwy) {
  d: path("M12 3v10m-3-3l3 3l3-3");
}

:global(.lny_l6bpa) {
  stroke-opacity: 0.4;
  d: path("M10 19a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
