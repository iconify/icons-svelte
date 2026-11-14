<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o46tho0ro"/><path class="j51f-ebgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:x-ray-wave" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j51f-ebgg) {
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.o46tho0ro) {
  d: path("M2.5 12C4 8 5.75 8 7.25 12s3.25 4 4.75 0s3.25-4 4.75 0s3.25 4 4.75 0");
}

</style>
