<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rm49aj31c"/><path class="k4nk-sxxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:takeaway-bag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k4nk-sxxv) {
  d: path("M5.5 14L8 12.5l2.5 1.5l2.5-1.5l2.5 1.5l2.5-1.5");
}

:global(.rm49aj31c) {
  d: path("M5.5 8h13l-1 12.5h-11ZM9 8V6a3 3 0 0 1 6 0v2");
}

</style>
