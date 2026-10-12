<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lyp7ak-rs"/><rect class="knwm6cc_h"/><path class="x56betbfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shutter-button" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.knwm6cc_h) {
  width: 8px;
  height: 4.5px;
  x: 8px;
  y: 10.75px;
  rx: 1.75px;
}

:global(.lyp7ak-rs) {
  width: 14.5px;
  height: 6px;
  x: 4.75px;
  y: 15.25px;
  rx: 2px;
}

:global(.x56betbfm) {
  d: path("M12 2.75v5M9.75 5.5L12 7.75l2.25-2.25");
}

</style>
