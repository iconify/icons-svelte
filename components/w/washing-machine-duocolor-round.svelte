<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="couc1ac6n"/><path class="bqeaqgbdj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:washing-machine-duocolor-round" {...props}></Icon>
<style>
:global(.bqeaqgbdj) {
  d: path("M4 7a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm0 2h16M8 6h.01M11 6h.01");
}

:global(.couc1ac6n) {
  stroke-opacity: 0.4;
  d: path("M9 15a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
