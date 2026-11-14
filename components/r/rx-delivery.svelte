<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kh6cjybjd"/><path class="q5t0-q9du"/><path class="d55yj2bsn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rx-delivery" {...props}></Icon>
<style>
:global(.d55yj2bsn) {
  d: path("M5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-8-11V9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kh6cjybjd) {
  d: path("M2.5 14.5h19V10l-3-3.5h-4v8");
}

:global(.q5t0-q9du) {
  d: path("M4.75 5.5h5.5A1.75 1.75 0 0 1 12 7.25v5.5a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 3 12.75v-5.5A1.75 1.75 0 0 1 4.75 5.5");
}

</style>
