<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ftqzjnb8u"/><path class="naxi-2ilz"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trailhead-outline-bold" {...props}></Icon>
<style>
:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.naxi-2ilz) {
  d: path("M6 5h10l3.5 3.5L16 12H6");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
