<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hxs7cr7lm"/><path class="grpcwaciz"/><path class="fy72pvbym"/><path class="bwel3nf-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:self-correct-outline-bold" {...props}></Icon>
<style>
:global(.bwel3nf-y) {
  d: path("m16 15 2 2 3 -3");
}

:global(.fy72pvbym) {
  d: path("M4 16h10");
}

:global(.grpcwaciz) {
  d: path("m4 10 6 -6");
}

:global(.hxs7cr7lm) {
  d: path("M4 7h10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
