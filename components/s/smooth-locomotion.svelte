<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lvvionm4c"/><path class="f977m53hk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smooth-locomotion" {...props}></Icon>
<style>
:global(.f977m53hk) {
  d: path("M18 4.25L21 5l-1.25 2.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lvvionm4c) {
  d: path("M4.5 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 3V15M3 20v-3a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v3Zm12-2c0-7 2-11 6-13");
}

</style>
