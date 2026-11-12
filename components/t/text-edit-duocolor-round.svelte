<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fm21oiyer"/><path class="ruaxyzbtr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-edit-duocolor-round" {...props}></Icon>
<style>
:global(.fm21oiyer) {
  stroke-opacity: 0.4;
  d: path("m3 21l3-3l3 3m4 0h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ruaxyzbtr) {
  d: path("M9 15v-3l8-8a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 1 0 2l-8 8zm6-9l3 3");
}

</style>
