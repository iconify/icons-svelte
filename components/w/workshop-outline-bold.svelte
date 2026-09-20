<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zugrvnb7t"/><path class="f5ieidcch"/><path class="q40roytdv"/><path class="gr2yy8pwl"/><path class="pkf-n2b8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:workshop-outline-bold" {...props}></Icon>
<style>
:global(.f5ieidcch) {
  d: path("M5 13v8");
}

:global(.gr2yy8pwl) {
  d: path("M8 13V6h9v7");
}

:global(.pkf-n2b8h) {
  d: path("M10 6a2.5 2.5 0 0 1 5 0");
}

:global(.q40roytdv) {
  d: path("M19 13v8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zugrvnb7t) {
  d: path("M2 13h20");
}

</style>
