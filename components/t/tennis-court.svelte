<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5i_88bgd"/><circle class="mc1uouhee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tennis-court" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mc1uouhee) {
  cx: 18.75px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.o5i_88bgd) {
  d: path("M18.7 5.05a7 5.5-45 1 1-9.9 9.9a7 5.5-45 1 1 9.9-9.9m-9.02 6.54l5.66-5.66m-3.18 8.14l5.66-5.66M8.8 14.95l-4.55 4.8");
}

</style>
