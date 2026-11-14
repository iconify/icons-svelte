<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5g1dbbam"/><path class="ruit5cbro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:telecom-van" {...props}></Icon>
<style>
:global(.f5g1dbbam) {
  d: path("M2.5 16.5V9a2 2 0 0 1 2-2H14l4 4h1.5a2 2 0 0 1 2 2v3.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ruit5cbro) {
  d: path("M4.75 18.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m10 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M4.5 4.25H13M13 7v4h5");
}

</style>
