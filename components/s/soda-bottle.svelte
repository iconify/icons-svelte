<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o30tisonq"/><path class="xv-xebuef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:soda-bottle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o30tisonq) {
  d: path("M10 6v2c0 1.5-3 2.5-3 5v7a1.5 1.5 0 0 0 1.5 1.5h7A1.5 1.5 0 0 0 17 20v-7c0-2.5-3-3.5-3-5V6m-3-3.5h2A1.5 1.5 0 0 1 14.5 4v.5A1.5 1.5 0 0 1 13 6h-2a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 11 2.5m0 15h.01");
}

:global(.xv-xebuef) {
  d: path("M11.5 13.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
