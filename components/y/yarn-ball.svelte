<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ql-bjpb9n"/><path class="lvhurd5zi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:yarn-ball" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lvhurd5zi) {
  d: path("M6 5.25c3.25 2 5.75 7 5 15m-.25-17.4c3 1.75 6.25 6 6.75 11.5M2.95 12.5c2.75.25 6 1.75 8.3 4M17 18.25c1.5 1.75 2.75 3 4.25 3");
}

:global(.ql-bjpb9n) {
  cx: 11.5px;
  cy: 11.5px;
  r: 8.75px;
}

</style>
