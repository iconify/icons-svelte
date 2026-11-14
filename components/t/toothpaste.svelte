<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g0-n62b0y"/><path class="lsg4qfbit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:toothpaste" {...props}></Icon>
<style>
:global(.g0-n62b0y) {
  d: path("m2.5 4.5l10 1l2.5 2v3l-2.5 2l-10 1ZM16.75 7za1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 16.75 11A1.75 1.75 0 0 1 15 9.25v-.5A1.75 1.75 0 0 1 16.75 7M5 4.75v8.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lsg4qfbit) {
  d: path("M18.5 9c3 0 3.25 4.5 0 5.5c-3 1-4 4.5-1 5h3");
}

</style>
