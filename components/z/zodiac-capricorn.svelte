<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p873oytrc"/><path class="fwgkvqbcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:zodiac-capricorn" {...props}></Icon>
<style>
:global(.fwgkvqbcp) {
  d: path("M15.75 15.25c0-1.75 1.25-3 2.75-3s2.75 1.25 2.75 3s-1.25 3-2.75 3c-2 0-3.5 1-4.5 2.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p873oytrc) {
  d: path("M3.75 4.75c1.5 0 2.5 1 3 2.5l3.25 11l3.5-11.5c.5-1.5 1.25-2 2.25-2c1.5 0 2 1.25 2 2.5v8");
}

</style>
