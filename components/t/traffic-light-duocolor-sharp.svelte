<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ihuibw2pp"/><path class="ctvcln5hp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:traffic-light-duocolor-sharp" {...props}></Icon>
<style>
:global(.ctvcln5hp) {
  d: path("M7 3h10v18H7Z");
}

:global(.ihuibw2pp) {
  stroke-opacity: 0.4;
  d: path("M11 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
