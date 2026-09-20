<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mh_3yqm3z"/><path class="mb3fb7bkl"/><path class="tdul-wdwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:xp-bar-outline-bold" {...props}></Icon>
<style>
:global(.mb3fb7bkl) {
  d: path("M17 10v10");
}

:global(.mh_3yqm3z) {
  d: path("M3 10h18v10H3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tdul-wdwn) {
  d: path("m9 6 3 -3 3 3");
}

</style>
