<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k2c5x4bmu"/><path class="ygs8-mynj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ship-duocolor-round" {...props}></Icon>
<style>
:global(.k2c5x4bmu) {
  stroke-opacity: 0.4;
  d: path("M2 20c.5.5 1 1 2 1c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2c1 0 1.5-.5 2-1");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ygs8-mynj) {
  d: path("m4 17l-1-3l9-3l9 3l-1 3M6 13V9a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v4M12 3v3m0 5v6");
}

</style>
