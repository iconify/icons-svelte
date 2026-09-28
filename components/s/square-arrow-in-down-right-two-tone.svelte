<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nf3dnhbiy"/><path class="ziusd-tnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-in-down-right-two-tone" {...props}></Icon>
<style>
:global(.nf3dnhbiy) {
  stroke-opacity: 0.4;
  d: path("M15 7L18 7C19.6569 7 21 8.3431 21 10L21 18C21 19.6569 19.6569 21 18 21L10 21C8.3431 21 7 19.6569 7 18L7 15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ziusd-tnj) {
  d: path("M3 3L10.5 10.5M3 11L10.5 11C10.7761 11 11 10.7761 11 10.5L11 3");
}

</style>
