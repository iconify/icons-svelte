<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rehbgwrxu"/><rect class="awisu_bpo"/><path class="khl37jain"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:text-gradient" {...props}></Icon>
<style>
:global(.awisu_bpo) {
  width: 18px;
  height: 3.75px;
  x: 3px;
  y: 17.25px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.khl37jain) {
  d: path("M7.5 17.25V21m4.5-3.75V21m4.5-3.75V21");
}

:global(.rehbgwrxu) {
  d: path("m5.5 14.25l6.5-11l6.5 11m-10.65-4h8.3");
}

</style>
