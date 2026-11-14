<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jvymac-ri"/><path class="htts0xb3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tennis-deuce" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.htts0xb3t) {
  d: path("M3.75 5.25a3.25 3.25 0 0 1 0 5.5m16.5-5.5a3.25 3.25 0 0 0 0 5.5M8 17h8m-8 3h8");
}

:global(.jvymac-ri) {
  d: path("M2.5 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
