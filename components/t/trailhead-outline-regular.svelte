<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ftqzjnb8u"/><path class="naxi-2ilz"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trailhead-outline-regular" {...props}></Icon>
<style>
:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.naxi-2ilz) {
  d: path("M6 5h10l3.5 3.5L16 12H6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

</style>
