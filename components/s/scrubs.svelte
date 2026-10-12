<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x6-osx0-e"/><rect class="e6jgnpbxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scrubs" {...props}></Icon>
<style>
:global(.e6jgnpbxj) {
  width: 3px;
  height: 3.25px;
  x: 12px;
  y: 11px;
  rx: 0.6px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x6-osx0-e) {
  d: path("m9.14 4.02l2.22 2.71q.64.77 1.28 0l2.22-2.71q.64-.77 1.57-.4l3.14 1.26q.93.37 1.05 1.36l.51 4.02q.12.99-.85 1.21l-1.31.31Q18 12 18 13v7.25q0 1-1 1H7q-1 0-1-1V13q0-1-.97-1.22l-1.31-.31q-.97-.22-.85-1.21l.51-4.02q.12-.99 1.05-1.36l3.14-1.26q.93-.37 1.57.4");
}

</style>
