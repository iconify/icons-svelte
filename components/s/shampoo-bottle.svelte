<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t0seeyjur"/><rect class="em5b05bqu"/><rect class="kb576ob0p"/><path class="xcjc1dbfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shampoo-bottle" {...props}></Icon>
<style>
:global(.em5b05bqu) {
  width: 4.5px;
  height: 2.5px;
  x: 9.75px;
  y: 6.25px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kb576ob0p) {
  width: 11.5px;
  height: 9.5px;
  x: 6.25px;
  y: 11.75px;
  rx: 3px;
}

:global(.t0seeyjur) {
  d: path("M7 3.5h7.5m-2.5 0v2.75");
}

:global(.xcjc1dbfr) {
  d: path("M9.5 16.5h5");
}

</style>
