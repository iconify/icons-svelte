<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i0n9pc8do"/><path class="i4owje5xd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tags-duocolor" {...props}></Icon>
<style>
:global(.i0n9pc8do) {
  stroke-opacity: 0.4;
  d: path("m15 6l5 5a1.414 1.414 0 0 1 0 2l-5 5");
}

:global(.i4owje5xd) {
  d: path("M6 6h2c.64 0 1.36.36 2 1l4 4a1.414 1.414 0 0 1 0 2l-4 4a1.414 1.414 0 0 1-2 0l-4-4c-.64-.64-1-1.36-1-2V8a2 2 0 0 1 2-2zm1 4h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
