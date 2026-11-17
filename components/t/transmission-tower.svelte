<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pipcavbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:transmission-tower" {...props}></Icon>
<style>
:global(.pipcavbkm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m6 21l4-12V6c0-.64.36-1.36 1-2a1.414 1.414 0 0 1 2 0c.64.64 1 1.36 1 2v3l4 12M4 12v-1a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v1M9 12l3 6l3-6m-8 6h10");
}

</style>
