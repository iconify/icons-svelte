<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g8xqzj5sl"/><path class="iusgy0bey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skull-archaeology" {...props}></Icon>
<style>
:global(.g8xqzj5sl) {
  d: path("M6.5 18.25V15A1.5 1.5 0 0 1 5 13.5v-3a7 7 0 0 1 14 0v3a1.5 1.5 0 0 1-1.5 1.5v3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iusgy0bey) {
  d: path("M2.5 21q9.5-8 19 0M7.75 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M9.5 20.25h.01m4.99 0h.01");
}

</style>
