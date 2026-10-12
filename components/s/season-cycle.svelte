<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpnpfkblo"/><path class="x8ij9qbzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:season-cycle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x8ij9qbzi) {
  d: path("M8.75 15.25c0-4.25 2.25-6.5 6.5-6.5c0 4.25-2.25 6.5-6.5 6.5");
}

:global(.zpnpfkblo) {
  d: path("M4.01 9.09a8.5 8.5 0 0 1 15.98 0m-2.04-.95l2.04.95l.95-2.04m-.95 7.86a8.5 8.5 0 0 1-15.98 0m2.04.95l-2.04-.95l-.95 2.04");
}

</style>
