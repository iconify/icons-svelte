<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sjmvcxbpe"/><path class="l0v-b4kbr"/><path class="ug4kkubvk"/><path class="ipv0cebdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transform-outline-regular" {...props}></Icon>
<style>
:global(.ipv0cebdm) {
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sjmvcxbpe) {
  d: path("M2 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.ug4kkubvk) {
  d: path("m13 9 3 3 -3 3");
}

</style>
