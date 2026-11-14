<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nflgqh6hp"/><path class="wfokt941n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ski-slope" {...props}></Icon>
<style>
:global(.nflgqh6hp) {
  d: path("M2.5 20L11 3.5L21.5 20");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wfokt941n) {
  d: path("M10.25 13c0 3-2.75 4-2.75 7m6.25-7c0 3-2.75 4-2.75 7");
}

</style>
