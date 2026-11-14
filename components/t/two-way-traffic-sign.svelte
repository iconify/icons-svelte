<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tpnyvdgai"/><path class="uwdo46j-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:two-way-traffic-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tpnyvdgai) {
  d: path("m14.475 4.475l5.05 5.05a3.5 3.5 0 0 1 0 4.95l-5.05 5.05a3.5 3.5 0 0 1-4.95 0l-5.05-5.05a3.5 3.5 0 0 1 0-4.95l5.05-5.05a3.5 3.5 0 0 1 4.95 0");
}

:global(.uwdo46j-s) {
  d: path("M9.5 15.5v-7m-1.75 1.75L9.5 8.5l1.75 1.75M14.5 8.5v7m-1.75-1.75l1.75 1.75l1.75-1.75");
}

</style>
