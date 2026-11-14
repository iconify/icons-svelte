<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jv4k-cbwj"/><path class="y5q52dczf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:soccer-jersey" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jv4k-cbwj) {
  d: path("M7 3h10a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 17 21H7a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 7 3");
}

:global(.y5q52dczf) {
  d: path("M9 3a3 3 0 0 0 6 0M8 9v12m8-12v12");
}

</style>
