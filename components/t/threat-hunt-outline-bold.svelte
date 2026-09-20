<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mxpxejnja"/><path class="su9etdbad"/><path class="uidmmjb0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:threat-hunt-outline-bold" {...props}></Icon>
<style>
:global(.mxpxejnja) {
  d: path("M3 5h8v6l-4 4 -4 -4Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.su9etdbad) {
  d: path("M14 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

:global(.uidmmjb0u) {
  d: path("m20 12.5 2 2");
}

</style>
