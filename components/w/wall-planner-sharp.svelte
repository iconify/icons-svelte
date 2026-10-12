<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="thi123b8x"/><path class="d7h7k6b1f"/><path class="zjsvsnq6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wall-planner-sharp" {...props}></Icon>
<style>
:global(.d7h7k6b1f) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 13.25h.01");
}

:global(.thi123b8x) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75zm0 4.75h18.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zjsvsnq6j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 13.25h6.25m-11 3.5h11.5");
}

</style>
