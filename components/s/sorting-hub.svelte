<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lsnqejxdn"/><path class="permose7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sorting-hub" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lsnqejxdn) {
  width: 5.5px;
  height: 5.5px;
  x: 2.75px;
  y: 9.25px;
  rx: 1px;
}

:global(.permose7q) {
  d: path("M8.25 12H20.5m-10.25 0l3.5-6h6.75m-10.25 6l3.5 6h6.75M18.25 3.75L20.5 6l-2.25 2.25m0 1.5L20.5 12l-2.25 2.25m0 1.5L20.5 18l-2.25 2.25");
}

</style>
