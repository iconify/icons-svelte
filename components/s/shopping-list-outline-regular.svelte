<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="diipsobkl"/><path class="pvve3lboo"/><path class="c6uw-ccfl"/><path class="n8sqmebht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shopping-list-outline-regular" {...props}></Icon>
<style>
:global(.c6uw-ccfl) {
  d: path("M7 14h10");
}

:global(.diipsobkl) {
  d: path("M5 3v18h14V3Z");
}

:global(.n8sqmebht) {
  d: path("M7 18h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pvve3lboo) {
  d: path("m7 8 2 2 4 -4");
}

</style>
