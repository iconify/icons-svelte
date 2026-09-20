<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="is1j44btv"/><path class="e65_6jbte"/><path class="n9baun0jc"/><path class="g4flvub6o"/><path class="oqj-o0b2r"/><path class="ljx4iubuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:schema-registry-duotone-thin" {...props}></Icon>
<style>
:global(.e65_6jbte) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.g4flvub6o) {
  d: path("M4 6V2.5h6L13.5 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.is1j44btv) {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ljx4iubuw) {
  d: path("M5 18h10");
}

:global(.n9baun0jc) {
  d: path("M2 10h20");
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

</style>
