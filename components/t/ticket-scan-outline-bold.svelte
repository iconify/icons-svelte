<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ee7dg944u"/><path class="zugrvnb7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ticket-scan-outline-bold" {...props}></Icon>
<style>
:global(.ee7dg944u) {
  d: path("M3 8h18v3l-2 2 2 2v3H3v-3l2 -2 -2 -2Z");
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
