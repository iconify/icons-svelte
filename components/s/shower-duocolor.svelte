<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y63qk5bnv"/><path class="jn_kjsbwe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shower-duocolor" {...props}></Icon>
<style>
:global(.jn_kjsbwe) {
  d: path("M13 7a4.243 4.243 0 0 0-6 6ZM4 4l3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y63qk5bnv) {
  stroke-opacity: 0.4;
  d: path("M10 16h.01M13 13h.01M16 10h.01M11 20h.01M14 17h.01M17 14h.01M20 11h.01");
}

</style>
