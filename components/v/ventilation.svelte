<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="vdo1j_06c"/><path class="ajbndmbii"/><path class="chsef1-ac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ventilation" {...props}></Icon>
<style>
:global(.ajbndmbii) {
  d: path("M12 10.25a2.5 2.25 90 0 1 0-5a2.5 2.25 90 0 1 0 5ZM13.5 13a2.5 2.25 30 0 1 4.25 2.5A2.5 2.25 30 0 1 13.5 13Z");
}

:global(.chsef1-ac) {
  d: path("M10.5 13a2.5 2.25 150 0 0-4.25 2.5A2.5 2.25 150 0 0 10.5 13Z");
}

:global(.g6ulkabjn) {
  d: path("M2.5 2.5h19v19h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vdo1j_06c) {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
