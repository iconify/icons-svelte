<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gh-bcfb0w"/><path class="uun5k1blf"/><path class="cty2dabyn"/><path class="kgr6yibsx"/><path class="qu18jzmnr"/><path class="kurig99-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smoothie-duotone-thin" {...props}></Icon>
<style>
:global(.cty2dabyn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 6 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gh-bcfb0w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 8v12h8V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kgr6yibsx) {
  d: path("M8 8v12h8V8");
}

:global(.kurig99-x) {
  d: path("m14 6 4 -4");
}

:global(.qu18jzmnr) {
  d: path("M8 8a4 4 0 0 1 8 0");
}

:global(.uun5k1blf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 8a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
