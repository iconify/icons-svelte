<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w1-2xqbmm"/><path class="od2v2ccvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smoke-simulation" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.od2v2ccvl) {
  d: path("m6.5 14l5.5 2.5l5.5-2.5M12 16.5v5m-3-12C7.25 7.75 10.75 5.75 9 3m6 6.5c-1.75-1.75 1.75-3.75 0-6.5");
}

:global(.w1-2xqbmm) {
  d: path("m12 11.5l5.5 2.5v5L12 21.5L6.5 19v-5Z");
}

</style>
