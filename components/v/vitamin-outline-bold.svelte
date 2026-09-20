<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h_n9wsbvm"/><path class="pohupsbfv"/><path class="f99n1fbkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vitamin-outline-bold" {...props}></Icon>
<style>
:global(.f99n1fbkg) {
  d: path("M16 7h6");
}

:global(.h_n9wsbvm) {
  d: path("m4 13 6 -6a4 4 0 0 1 5 5l-6 6a4 4 0 0 1 -5 -5");
}

:global(.pohupsbfv) {
  d: path("M19 4v6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
