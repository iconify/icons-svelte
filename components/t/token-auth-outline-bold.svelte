<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sy-mrrsuv"/><path class="it83nbbll"/><path class="a_lj6jt5i"/><path class="zy54a7bml"/><path class="zn_a46_dj"/><path class="yg3iw3bty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:token-auth-outline-bold" {...props}></Icon>
<style>
:global(.a_lj6jt5i) {
  d: path("M9 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.it83nbbll) {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sy-mrrsuv) {
  d: path("M2 12a4 4 0 0 1 4 -4h5a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

:global(.yg3iw3bty) {
  d: path("M21 12v2.5");
}

:global(.zn_a46_dj) {
  d: path("M18 12v3");
}

:global(.zy54a7bml) {
  d: path("M17 12h4");
}

</style>
