<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xycf6-bdn"/><path class="i-2dnzb7m"/><path class="qw7b_6b1t"/><path class="gfk1uw7pu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wine-tasting-outline-bold" {...props}></Icon>
<style>
:global(.gfk1uw7pu) {
  d: path("M9 8q3 3 6 0");
}

:global(.i-2dnzb7m) {
  d: path("M12 14v6");
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xycf6-bdn) {
  d: path("M7 4h10v4c0 4 -2 6 -5 6s-5 -2 -5 -6Z");
}

</style>
