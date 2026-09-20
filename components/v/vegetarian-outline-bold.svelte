<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="by2xacctu"/><path class="pgsklob1p"/><path class="sjot3p-qh"/><path class="sx4d4gbbz"/><path class="rhu0tub0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vegetarian-outline-bold" {...props}></Icon>
<style>
:global(.by2xacctu) {
  d: path("M6 3v5");
}

:global(.pgsklob1p) {
  d: path("M10 3v5");
}

:global(.rhu0tub0r) {
  d: path("M14 18c0 -5 3 -8 8 -8 0 5 -3 8 -8 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sjot3p-qh) {
  d: path("M6 8h4");
}

:global(.sx4d4gbbz) {
  d: path("M8 8v13");
}

</style>
