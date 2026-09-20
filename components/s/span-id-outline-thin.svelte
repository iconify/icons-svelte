<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lqcp5xb1v"/><path class="t3vzob-fn"/><path class="uxyzhxvwz"/><path class="s3kgq-l9e"/><path class="gvu3jzbph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:span-id-outline-thin" {...props}></Icon>
<style>
:global(.gvu3jzbph) {
  d: path("M14 9.5v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lqcp5xb1v) {
  d: path("M4 3h16");
}

:global(.s3kgq-l9e) {
  d: path("M10 9.5v5");
}

:global(.t3vzob-fn) {
  d: path("M2 12a6 6 0 0 1 6 -6h8a6 6 0 0 1 6 6 6 6 0 0 1 -6 6H8a6 6 0 0 1 -6 -6");
}

:global(.uxyzhxvwz) {
  d: path("M7 12h10");
}

</style>
