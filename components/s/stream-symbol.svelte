<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymouieb4g"/><path class="s9hdorbgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stream-symbol" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s9hdorbgn) {
  d: path("M9.5 2.5C9.5 8 20 6.5 20 12S9.5 16 9.5 21.5");
}

:global(.ymouieb4g) {
  d: path("M4.5 2.5C4.5 8 15 6.5 15 12S4.5 16 4.5 21.5");
}

</style>
