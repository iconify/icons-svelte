<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h96v87b2m"/><path class="j1kxoubdj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:terminal-tab" {...props}></Icon>
<style>
:global(.h96v87b2m) {
  d: path("M6 7.5h12a3.5 3.5 0 0 1 3.5 3.5v6.5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5V11A3.5 3.5 0 0 1 6 7.5m-1 0V5a1.5 1.5 0 0 1 1.5-1.5h6A1.5 1.5 0 0 1 14 5v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j1kxoubdj) {
  d: path("m6.5 11.75l2.75 2.75l-2.75 2.75m5 0H16");
}

</style>
