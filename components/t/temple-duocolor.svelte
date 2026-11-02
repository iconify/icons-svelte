<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ce59h9myo"/><path class="u1arpjfde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:temple-duocolor" {...props}></Icon>
<style>
:global(.ce59h9myo) {
  stroke-opacity: 0.4;
  d: path("M10 21v-3a2 2 0 1 1 4 0v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u1arpjfde) {
  d: path("M3 21h7m4 0h7M6 12h12a3 3 0 0 0 3-3c-5 0-8-3-9-6c-1 3-4 6-9 6a3 3 0 0 0 3 3m0 9v-9m12 9v-9");
}

</style>
