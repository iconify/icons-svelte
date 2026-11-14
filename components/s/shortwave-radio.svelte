<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-5zhgbzr"/><path class="zp9oudbgm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shortwave-radio" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-5zhgbzr) {
  d: path("M6 8h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 8m9 0l5-5.5");
}

:global(.zp9oudbgm) {
  d: path("M5.25 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m8.75 0h4.5");
}

</style>
