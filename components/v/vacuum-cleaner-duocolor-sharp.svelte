<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sm-xfbcsk"/><path class="fy88v4-gd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:vacuum-cleaner-duocolor-sharp" {...props}></Icon>
<style>
:global(.fy88v4-gd) {
  d: path("M3 17a4 4 0 1 1 8 0v4H3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sm-xfbcsk) {
  stroke-opacity: 0.4;
  d: path("M7 13V8c0-4 6-5 7-2l5 15m-3 0h5");
}

</style>
