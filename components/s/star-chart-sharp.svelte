<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pocksj24m"/><circle class="a56ludvdj"/><circle class="imf88e1vk"/><circle class="i093j3bwh"/><path class="bwdbcrbhn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:star-chart-sharp" {...props}></Icon>
<style>
:global(.a56ludvdj) {
  cx: 4px;
  cy: 19.5px;
  r: 1.25px;
}

:global(.bwdbcrbhn) {
  d: path("M18 2.75q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25Z");
}

:global(.i093j3bwh) {
  cx: 13.5px;
  cy: 16px;
  r: 1.25px;
}

:global(.imf88e1vk) {
  cx: 8px;
  cy: 11px;
  r: 1.25px;
}

:global(.pocksj24m) {
  d: path("m4.85 17.69l2.3-4.88m2.33-.46l2.54 2.3m2.3-.47l1.32-2.94");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
