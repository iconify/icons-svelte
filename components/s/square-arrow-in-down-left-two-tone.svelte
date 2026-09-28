<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dcase-teq"/><path class="x-as5ev2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-in-down-left-two-tone" {...props}></Icon>
<style>
:global(.dcase-teq) {
  stroke-opacity: 0.4;
  d: path("M9 7L6 7C4.3431 7 3 8.3431 3 10L3 18C3 19.6569 4.3431 21 6 21L14 21C15.6569 21 17 19.6569 17 18L17 15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x-as5ev2f) {
  d: path("M21 3L13.5 10.5M21 11L13.5 11C13.2239 11 13 10.7761 13 10.5L13 3");
}

</style>
