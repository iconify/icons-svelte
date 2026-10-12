<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ynf6gdd5u"/><rect class="w9r89ccbw"/><path class="cgifldh5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wire" {...props}></Icon>
<style>
:global(.cgifldh5d) {
  d: path("m17.5 10.5l3.75-1.75M17.5 12h3.75m-3.75 1.5l3.75 1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w9r89ccbw) {
  width: 5.5px;
  height: 4.5px;
  x: 10.25px;
  y: 9.75px;
  rx: 1.25px;
}

:global(.ynf6gdd5u) {
  d: path("M2.75 18.25C7.25 18.25 6 12 10.5 12");
}

</style>
