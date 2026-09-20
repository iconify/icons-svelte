<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="filuri95n"/><path class="p9fnnqwai"/><path class="g7rxpleju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-chill-outline-regular" {...props}></Icon>
<style>
:global(.filuri95n) {
  d: path("M8 4v8m-4 0 8 -8");
}

:global(.g7rxpleju) {
  d: path("M4 20h14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p9fnnqwai) {
  d: path("M4 16h11a3 3 0 1 1 -3 3");
}

</style>
