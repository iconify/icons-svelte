<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yoftwf7ei"/><path class="qzpg-bc7o"/><path class="ic_pehd5a"/><path class="ofzwylwbi"/><path class="ejtyvbbdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:water-meter-outline-regular" {...props}></Icon>
<style>
:global(.ejtyvbbdg) {
  d: path("M17 15v4");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ofzwylwbi) {
  d: path("M7 15v4");
}

:global(.qzpg-bc7o) {
  d: path("m12 6 2 2a2.8 2.8 0 1 1 -4 0Z");
}

:global(.yoftwf7ei) {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
