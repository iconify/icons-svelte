<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sgirdibdt"/><circle class="ikirqmbyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trampoline" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ikirqmbyo) {
  cx: 12px;
  cy: 4.25px;
  r: 1.5px;
}

:global(.sgirdibdt) {
  d: path("M2.75 12c0-1.93 4.14-3.5 9.25-3.5s9.25 1.57 9.25 3.5s-4.14 3.5-9.25 3.5s-9.25-1.57-9.25-3.5M5 14.4v6.85m14-6.85v6.85m-7-5.75v5.75");
}

</style>
