<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vrj8akbcc"/><path class="bxyh6cbnl"/><path class="ync9d6bsc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vinyl-record-outline-thin" {...props}></Icon>
<style>
:global(.bxyh6cbnl) {
  d: path("M9 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vrj8akbcc) {
  d: path("M3 4v16h14V4Z");
}

:global(.ync9d6bsc) {
  d: path("M14 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
