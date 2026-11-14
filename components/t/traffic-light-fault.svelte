<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m0mdbousf"/><path class="mqez4ubvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:traffic-light-fault" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m0mdbousf) {
  d: path("M8.875 2h.25A4.375 4.375 0 0 1 13.5 6.375v11.25A4.375 4.375 0 0 1 9.125 22h-.25A4.375 4.375 0 0 1 4.5 17.625V6.375A4.375 4.375 0 0 1 8.875 2");
}

:global(.mqez4ubvk) {
  d: path("M7.5 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m11-4v4m0 3h.01");
}

</style>
