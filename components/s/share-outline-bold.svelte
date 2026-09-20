<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zirb-hbnv"/><path class="x8ux9pb9v"/><path class="dvobmj5db"/><path class="otd842a5m"/><path class="x6ykmmben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:share-outline-bold" {...props}></Icon>
<style>
:global(.dvobmj5db) {
  d: path("M14 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.otd842a5m) {
  d: path("m9.5 10.5 5 -5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x6ykmmben) {
  d: path("m9.5 13.5 5 5");
}

:global(.x8ux9pb9v) {
  d: path("M14 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zirb-hbnv) {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
