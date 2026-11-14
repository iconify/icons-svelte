<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w2hy_eqxc"/><path class="qpwpt12nh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:steakhouse" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qpwpt12nh) {
  d: path("M7.25 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.w2hy_eqxc) {
  d: path("M5 12.75c-2-3-.5-8 4.5-8.5c3.5-.5 5 2 8 2.5s3.5 3.5 2 5c-2 2-7.5 2.5-10.5 2.5c-2 0-3.25-.5-4-1.5m-2.5 4.5h19C20.75 19.5 17 20.5 12 20.5s-8.75-1-9.5-3.25");
}

</style>
