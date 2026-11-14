<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q8ovzjbcc"/><path class="qfup4acnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:specimen-label" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q8ovzjbcc) {
  d: path("M7.5 5h12c1.1 0 2 .9 2 2v10c0 1.1-.9 2-2 2h-12l-5-7Z");
}

:global(.qfup4acnm) {
  d: path("M5.75 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4.75-3.5v7m2.5-7v7m2.5-7v7m2.5-7v7");
}

</style>
