<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="me4vljbbp"/><path class="kay0b-bev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:store" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kay0b-bev) {
  d: path("M10 21.25V18a2 2 0 0 1 4 0v3.25");
}

:global(.me4vljbbp) {
  d: path("M5.4 3.25h13.2a1.5 1.5 0 0 1 1.4.97l1.25 3.28v.75a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5V7.5L4 4.22a1.5 1.5 0 0 1 1.4-.97m3.85 0l-.5 7.5m6-7.5l.5 7.5m-10.5 2.5h14.5v6a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2Z");
}

</style>
