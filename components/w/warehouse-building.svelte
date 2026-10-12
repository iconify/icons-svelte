<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tzvmh1l8q"/><path class="t2jk5r0rp"/><rect class="f7r-dwbvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:warehouse-building" {...props}></Icon>
<style>
:global(.f7r-dwbvl) {
  width: 5px;
  height: 2.5px;
  x: 9.5px;
  y: 8px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t2jk5r0rp) {
  d: path("M5.75 21.25v-6h5v6m2.5 0v-6h5v6");
}

:global(.tzvmh1l8q) {
  d: path("M2.75 21.25V11a9.25 7.25 0 0 1 18.5 0v10.25Z");
}

</style>
