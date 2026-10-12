<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fq3z78bdg"/><rect class="k4jgzab0f"/><rect class="jds4z8bpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scripture-scroll" {...props}></Icon>
<style>
:global(.fq3z78bdg) {
  d: path("M5.5 5.75h13v12.5h-13ZM8.5 9h7m-7 3h7m-7 3H13");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jds4z8bpz) {
  width: 16.5px;
  height: 3px;
  x: 3.75px;
  y: 18.25px;
  rx: 1.5px;
}

:global(.k4jgzab0f) {
  width: 16.5px;
  height: 3px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
