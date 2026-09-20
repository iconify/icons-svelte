<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f-t_rcb_j"/><path class="qbb6npcvm"/><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="df40ebbiv"/><path class="c2yafbc1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stamp-card-duotone-regular" {...props}></Icon>
<style>
:global(.c2yafbc1d) {
  d: path("m13.5 14 2 2 3.5 -3.5");
}

:global(.df40ebbiv) {
  d: path("M6.5 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f-t_rcb_j) {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k6fi9qmtq) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.qbb6npcvm) {
  fill: currentColor;
  d: path("M6.5 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
