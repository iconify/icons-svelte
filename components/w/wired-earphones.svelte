<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="q3jop5grj"/><circle class="tq0ogqbac"/><path class="xe5j2gbzm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wired-earphones" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q3jop5grj) {
  cx: 7px;
  cy: 5.25px;
  r: 2.5px;
}

:global(.tq0ogqbac) {
  cx: 17px;
  cy: 5.25px;
  r: 2.5px;
}

:global(.xe5j2gbzm) {
  d: path("M7 7.75v3.5a5 5 0 0 0 5 5v5m5-13.5v3.5a5 5 0 0 1-5 5");
}

</style>
