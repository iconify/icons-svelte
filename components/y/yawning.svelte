<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="v3b1efb1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:yawning" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

:global(.v3b1efb1j) {
  d: path("m6.5 9l3 1.5l-3 1.5m11-3l-3 1.5l3 1.5m-8 4.5a2.5 3 0 1 0 5 0a2.5 3 0 1 0-5 0");
}

</style>
