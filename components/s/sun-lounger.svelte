<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mkksvcbdq"/><path class="uyiddkvas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sun-lounger" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mkksvcbdq) {
  cx: 7px;
  cy: 7.5px;
  r: 2.75px;
}

:global(.uyiddkvas) {
  d: path("M2.75 15.25h12l3.75-5.5m-13.25 5.5v4.5m9.5-4.5v4.5");
}

</style>
