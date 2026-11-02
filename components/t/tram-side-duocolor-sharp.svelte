<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c26ugccyd"/><path class="lv2h2ober"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tram-side-duocolor-sharp" {...props}></Icon>
<style>
:global(.c26ugccyd) {
  stroke-opacity: 0.4;
  d: path("M9 3h6m-3 0v4M3 21h18");
}

:global(.lv2h2ober) {
  d: path("M3 7h18v10H3zm0 5h18M8 7v5m5-5v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
