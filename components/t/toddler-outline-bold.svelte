<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ddr0zpdgr"/><path class="n-fiqpbfy"/><path class="uxyzhxvwz"/><path class="eev_c9mlp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:toddler-outline-bold" {...props}></Icon>
<style>
:global(.ddr0zpdgr) {
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.eev_c9mlp) {
  d: path("m7 20 5 -5 5 5");
}

:global(.n-fiqpbfy) {
  d: path("M12 10v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

</style>
