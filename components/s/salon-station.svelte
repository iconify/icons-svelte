<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0ev4mbcj"/><path class="ilk7xub_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:salon-station" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ilk7xub_b) {
  d: path("M8.5 8.5A4 4 0 0 1 11 5.25m-5 12h7m-5.5 0V21m3-3.75V21");
}

:global(.n0ev4mbcj) {
  d: path("M5.5 8.25a6.5 6.25 0 1 0 13 0a6.5 6.25 0 1 0-13 0M3.5 21h17");
}

</style>
