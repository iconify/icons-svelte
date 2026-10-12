<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="y-fd6pbmc"/><circle class="lqrgq66ey"/><path class="i5sjkluuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:unfollow" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i5sjkluuw) {
  d: path("M6.25 14.5a4 4 0 0 1 8 0m2.5 4.25h4");
}

:global(.lqrgq66ey) {
  cx: 10.25px;
  cy: 8.25px;
  r: 2.25px;
}

:global(.y-fd6pbmc) {
  cx: 10.25px;
  cy: 10.25px;
  r: 7.5px;
}

</style>
