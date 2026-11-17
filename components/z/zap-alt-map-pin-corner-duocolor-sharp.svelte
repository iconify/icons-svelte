<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a1mbuxbpb"/><path class="j20rde88o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-alt-map-pin-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.a1mbuxbpb) {
  stroke-opacity: 0.4;
  d: path("M17 21c-1.5-1-3-3-3-5a3 3 0 0 1 6 0c0 2-1.5 4-3 5m0-5h.01");
}

:global(.j20rde88o) {
  d: path("M13.394 10H10l4-7H7l-4 9h3l-2 9l6.085-6.085");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
