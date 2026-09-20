<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nzpsuduik"/><path class="z3c71dbbg"/><path class="ez39r6bms"/><path class="j11us-bgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:video-frame-ai-outline-regular" {...props}></Icon>
<style>
:global(.ez39r6bms) {
  d: path("M17 3v18");
}

:global(.j11us-bgd) {
  d: path("M10.5 9v6l3 -3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.z3c71dbbg) {
  d: path("M7 3v18");
}

</style>
