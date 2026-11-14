<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nflgqh6hp"/><path class="wfokt941n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ski-slope" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nflgqh6hp) {
  d: path("M2.5 20L11 3.5L21.5 20");
}

:global(.wfokt941n) {
  d: path("M10.25 13c0 3-2.75 4-2.75 7m6.25-7c0 3-2.75 4-2.75 7");
}

</style>
