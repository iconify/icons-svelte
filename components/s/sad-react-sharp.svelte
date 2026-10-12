<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bnpmawgqy"/><path class="m_apzdbts"/><path class="dhffpb4-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sad-react-sharp" {...props}></Icon>
<style>
:global(.bnpmawgqy) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.3 19.43a8.75 8.75 0 1 0-4.23-4.23l-.67 4.35l-.213 1.281L4.4 20.5Z");
}

:global(.dhffpb4-w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 15.25L12 11.757l2.75 3.493m2.5-4.25l1 1.5v.5a1 1 0 0 1-2 0v-.5z");
}

:global(.m_apzdbts) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9.75h.01m5.49 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
