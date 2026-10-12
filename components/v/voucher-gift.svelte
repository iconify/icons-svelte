<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jh8sg_bol"/><path class="i78zpep2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:voucher-gift" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i78zpep2n) {
  d: path("M8.25 5.75v12.5m-5.5-7h18.5m-13 0c-.75-3-3-3.75-3-1.25c0 1.5 1.75 1.25 3 1.25c.75-3 3-3.75 3-1.25c0 1.5-1.75 1.25-3 1.25");
}

:global(.jh8sg_bol) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 2px;
}

</style>
