<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z3x0zqbqu"/><rect class="meggsqlav"/><path class="ocvhuaccq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sticky-keys" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.meggsqlav) {
  width: 8px;
  height: 10.5px;
  x: 13.25px;
  y: 6.75px;
  rx: 2px;
}

:global(.ocvhuaccq) {
  d: path("M6.75 14.5v-4.25M5 12l1.75-1.75L8.5 12m7.25 0h3M5 20.75h14");
}

:global(.z3x0zqbqu) {
  width: 8px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2px;
}

</style>
