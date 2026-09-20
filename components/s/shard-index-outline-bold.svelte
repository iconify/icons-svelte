<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b7nacdcee"/><path class="f8c172gmh"/><path class="qnmmmsbha"/><path class="zhf4ld96p"/><path class="tk_gkbbsy"/><path class="czv374byt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shard-index-outline-bold" {...props}></Icon>
<style>
:global(.b7nacdcee) {
  d: path("M3 6h6");
}

:global(.czv374byt) {
  d: path("M10 16h11");
}

:global(.f8c172gmh) {
  d: path("M12 6h9");
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tk_gkbbsy) {
  d: path("M3 16h4");
}

:global(.zhf4ld96p) {
  d: path("M17 11h4");
}

</style>
