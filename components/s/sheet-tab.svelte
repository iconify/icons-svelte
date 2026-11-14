<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g4n3adxtc"/><path class="ndgw97uiq"/><path class="ebgu_ibkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sheet-tab" {...props}></Icon>
<style>
:global(.ebgu_ibkn) {
  d: path("M15.25 17.5h3.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 18.75 21h-3.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

:global(.g4n3adxtc) {
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5V11a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 11V6.5A3.5 3.5 0 0 1 6.5 3M3 7.5h18M9 3v11.5M15 3v11.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ndgw97uiq) {
  fill: currentColor;
  d: path("M5.25 17.5h3.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 8.75 21h-3.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
