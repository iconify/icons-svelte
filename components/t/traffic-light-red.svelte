<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9qnado0x"/><path class="hht462ksi"/><path class="r1bg-_r0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:traffic-light-red" {...props}></Icon>
<style>
:global(.hht462ksi) {
  fill: currentColor;
  d: path("M9.75 6.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r1bg-_r0h) {
  d: path("M10.5 12.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.z9qnado0x) {
  d: path("M11.75 2h.5a5.25 5.25 0 0 1 5.25 5.25v9.5A5.25 5.25 0 0 1 12.25 22h-.5a5.25 5.25 0 0 1-5.25-5.25v-9.5A5.25 5.25 0 0 1 11.75 2");
}

</style>
