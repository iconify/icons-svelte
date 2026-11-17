<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q9mp-7b7p"/><path class="ns9_4pvvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:smoke-detector-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ns9_4pvvn) {
  d: path("M3 3h18v4H3Zm4 4v4h10V7");
}

:global(.q9mp-7b7p) {
  stroke-opacity: 0.4;
  d: path("M9 15c1.5.75 1.5 2.25 0 3s-1.5 2.25 0 3m6-6c1.5.75 1.5 2.25 0 3s-1.5 2.25 0 3");
}

</style>
