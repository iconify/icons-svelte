<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iw-m9zbcy"/><path class="bo69k3bvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:spinner-duocolor" {...props}></Icon>
<style>
:global(.bo69k3bvm) {
  d: path("M21 12a9 9 0 0 1-18 0");
}

:global(.iw-m9zbcy) {
  stroke-opacity: 0.4;
  d: path("M3 12a9 9 0 0 1 9-9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
