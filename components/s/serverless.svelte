<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ru3i_z4nd"/><path class="jo17nzbib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:serverless" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jo17nzbib) {
  d: path("M9.75 10.25h.75a.85.85 0 0 1 .77.5l2.68 5h.55m-2.7-3l-2.05 3");
}

:global(.ru3i_z4nd) {
  d: path("M7 18.25a4 4 0 0 1-.73-7.93a5.75 5.75 0 0 1 11.46 0a4 4 0 0 1-.73 7.93Z");
}

</style>
