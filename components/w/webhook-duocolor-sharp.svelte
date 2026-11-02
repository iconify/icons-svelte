<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzu91sbxz"/><path class="xco7i1vqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:webhook-duocolor-sharp" {...props}></Icon>
<style>
:global(.jzu91sbxz) {
  stroke-opacity: 0.4;
  d: path("M16 7a4 4 0 1 0-8 0v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xco7i1vqu) {
  d: path("M4 17a4 4 0 1 0 8 0h4m0 4a4 4 0 1 0 0-8h-4V7");
}

</style>
