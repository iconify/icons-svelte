<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3wzw5b1b"/><path class="vcnqpdg7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shoe-polish" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r3wzw5b1b) {
  d: path("M4 14a8 2.25 0 1 0 16 0a8 2.25 0 1 0-16 0");
}

:global(.vcnqpdg7c) {
  d: path("M4 14v4a8 2.25 0 0 0 16 0v-4M3.833 8.46l9.959-5.75a1.25 1.25 0 0 1 1.707.457a1.25 1.25 0 0 1-.457 1.708l-9.959 5.75a1.25 1.25 0 0 1-1.708-.458a1.25 1.25 0 0 1 .458-1.707");
}

</style>
