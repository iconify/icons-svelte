<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g58rs14ba"/><path class="f73i47bnv"/><path class="qik8460ao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:weights-outline-regular" {...props}></Icon>
<style>
:global(.f73i47bnv) {
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.g58rs14ba) {
  d: path("M4 11a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qik8460ao) {
  d: path("M5 21h14");
}

</style>
