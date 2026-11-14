<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j1bp8mw5b"/><path class="qzei6tbgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:transistor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j1bp8mw5b) {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0m6.5-4.5v9m0-6l6-3.5m-6 6.5l6 3.5");
}

:global(.qzei6tbgo) {
  d: path("m14.815 16.315l.12.12a.633.633 0 0 1-.31 1.065a.733.733 0 0 1-.875-.875a.633.633 0 0 1 1.065-.31");
}

</style>
