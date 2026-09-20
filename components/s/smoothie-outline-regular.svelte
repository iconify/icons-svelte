<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kgr6yibsx"/><path class="qu18jzmnr"/><path class="kurig99-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smoothie-outline-regular" {...props}></Icon>
<style>
:global(.kgr6yibsx) {
  d: path("M8 8v12h8V8");
}

:global(.kurig99-x) {
  d: path("m14 6 4 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qu18jzmnr) {
  d: path("M8 8a4 4 0 0 1 8 0");
}

</style>
