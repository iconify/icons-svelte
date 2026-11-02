<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="adiypubxg"/><path class="e9jl5nxyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-duocolor-sharp" {...props}></Icon>
<style>
:global(.adiypubxg) {
  stroke-opacity: 0.4;
  d: path("M3 8h18");
}

:global(.e9jl5nxyo) {
  d: path("M3 8V4h18v16H3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
