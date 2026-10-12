<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="me_-ph-rh"/><path class="gvu5eetdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:terrace-farm" {...props}></Icon>
<style>
:global(.gvu5eetdc) {
  d: path("M11 21.25V17.5h3.5V14H18v-3.5h3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.me_-ph-rh) {
  d: path("M3.53 20.72L20.72 3.53q.53-.53.53.22V20.5q0 .75-.75.75H3.75q-.75 0-.22-.53");
}

</style>
