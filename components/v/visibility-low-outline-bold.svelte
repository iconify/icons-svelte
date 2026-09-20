<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rp243mbkd"/><path class="bo51iypxr"/><path class="piohzog1p"/><path class="irm-6r_xs"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:visibility-low-outline-bold" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.irm-6r_xs) {
  d: path("M3 17v4");
}

:global(.piohzog1p) {
  d: path("M3 19h9");
}

:global(.rp243mbkd) {
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
