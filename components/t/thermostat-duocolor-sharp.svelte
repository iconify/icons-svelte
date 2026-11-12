<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j024w9uja"/><path class="p47hv7byv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:thermostat-duocolor-sharp" {...props}></Icon>
<style>
:global(.j024w9uja) {
  stroke-opacity: 0.4;
  d: path("M14 8h2m-2 3h1");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p47hv7byv) {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m7-5v6m-2 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
