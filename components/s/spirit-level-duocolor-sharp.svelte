<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b8vix7b6y"/><path class="totd-lnyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:spirit-level-duocolor-sharp" {...props}></Icon>
<style>
:global(.b8vix7b6y) {
  stroke-opacity: 0.4;
  d: path("M10 12a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.totd-lnyp) {
  d: path("M3 7h18v10H3Zm4 3v4m10-4v4");
}

</style>
