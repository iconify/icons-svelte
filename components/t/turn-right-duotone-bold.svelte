<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q30u6675d"/><path class="kt3044gyi"/><path class="prbs3ccnp"/><path class="eki_s5bnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turn-right-duotone-bold" {...props}></Icon>
<style>
:global(.eki_s5bnj) {
  d: path("m14 6 3 3 -3 3");
}

:global(.kt3044gyi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.prbs3ccnp) {
  d: path("M8 21V9h9");
}

:global(.q30u6675d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 21V9h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
