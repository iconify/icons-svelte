<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u7pjc2b7b"/><path class="j6i5yqb-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-back-duocolor-sharp" {...props}></Icon>
<style>
:global(.j6i5yqb-r) {
  d: path("M20 5L8 12l12 7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u7pjc2b7b) {
  stroke-opacity: 0.4;
  d: path("M4 5v14");
}

</style>
