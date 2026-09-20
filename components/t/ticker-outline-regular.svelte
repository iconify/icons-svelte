<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h_ahrlbwq"/><path class="c6ge0ib5p"/><path class="ywd80sbef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ticker-outline-regular" {...props}></Icon>
<style>
:global(.c6ge0ib5p) {
  d: path("M15 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

:global(.h_ahrlbwq) {
  d: path("M2 10a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ywd80sbef) {
  d: path("M5 13.5 7.5 11l2.5 2.5 2.5 -2.5");
}

</style>
