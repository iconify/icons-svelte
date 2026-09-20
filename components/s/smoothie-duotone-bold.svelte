<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="utsjhv8mh"/><path class="ab2bllbak"/><path class="mj6n4crmc"/><path class="kgr6yibsx"/><path class="qu18jzmnr"/><path class="kurig99-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smoothie-duotone-bold" {...props}></Icon>
<style>
:global(.ab2bllbak) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 8a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kgr6yibsx) {
  d: path("M8 8v12h8V8");
}

:global(.kurig99-x) {
  d: path("m14 6 4 -4");
}

:global(.mj6n4crmc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 6 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qu18jzmnr) {
  d: path("M8 8a4 4 0 0 1 8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.utsjhv8mh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 8v12h8V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
