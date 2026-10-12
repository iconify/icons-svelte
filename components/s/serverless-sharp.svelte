<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ru3i_z4nd"/><path class="wi9t6rbcy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:serverless-sharp" {...props}></Icon>
<style>
:global(.ru3i_z4nd) {
  d: path("M7 18.25a4 4 0 0 1-.73-7.93a5.75 5.75 0 0 1 11.46 0a4 4 0 0 1-.73 7.93Z");
}

:global(.wi9t6rbcy) {
  d: path("M9.75 10.25h.75l.545.003l.225.497l2.68 5h.55m-2.7-3l-2.05 3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
