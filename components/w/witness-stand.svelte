<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="g828vzbqg"/><path class="o-18exbff"/><rect class="qc0t40bkh"/><path class="pj5spw6ag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:witness-stand" {...props}></Icon>
<style>
:global(.g828vzbqg) {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o-18exbff) {
  d: path("M8 12a4 2.5 0 0 1 8 0Z");
}

:global(.pj5spw6ag) {
  d: path("M7.25 15.5h9.5");
}

:global(.qc0t40bkh) {
  width: 16.5px;
  height: 9.25px;
  x: 3.75px;
  y: 12px;
  rx: 1.5px;
}

</style>
