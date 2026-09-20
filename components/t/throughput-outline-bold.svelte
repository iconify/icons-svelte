<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zuuudpbwi"/><path class="dzvfone4k"/><path class="k134iabcj"/><path class="cks97xg-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:throughput-outline-bold" {...props}></Icon>
<style>
:global(.cks97xg-s) {
  d: path("m14 13 3 3 -3 3");
}

:global(.dzvfone4k) {
  d: path("m14 5 3 3 -3 3");
}

:global(.k134iabcj) {
  d: path("M3 16h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zuuudpbwi) {
  d: path("M3 8h14");
}

</style>
