<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o77iwv87c"/><path class="c8jtagpjt"/><path class="leo1-zbey"/><path class="l_u_8t5pe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rsvp-duotone-regular" {...props}></Icon>
<style>
:global(.c8jtagpjt) {
  d: path("M7 9v10h14V9Z");
}

:global(.l_u_8t5pe) {
  d: path("m6 11 -3 3 3 3");
}

:global(.leo1-zbey) {
  d: path("m7 9 7 7 7 -7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o77iwv87c) {
  fill: currentColor;
  d: path("M7 9v10h14V9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
