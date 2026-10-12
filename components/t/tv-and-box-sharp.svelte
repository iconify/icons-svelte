<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g-rtc5-ic"/><path class="s7hdf8bld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tv-and-box-sharp" {...props}></Icon>
<style>
:global(.g-rtc5-ic) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v11.5H2.75zm3.5 14.5h11.5v4H6.25z");
}

:global(.s7hdf8bld) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.75 19.25h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
