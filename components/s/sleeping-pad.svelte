<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fr43wg0ji"/><path class="f_0l5nbmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sleeping-pad" {...props}></Icon>
<style>
:global(.f_0l5nbmu) {
  d: path("M2.5 12v3a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2v-3M8.75 7v7m6.5-7v7");
}

:global(.fr43wg0ji) {
  d: path("M6 7h12a3.5 3.5 0 0 1 3.5 3.5A3.5 3.5 0 0 1 18 14H6a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 6 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
