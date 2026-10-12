<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jolwk_1dx"/><path class="ip2emh-hq"/><rect class="jh2trtb0z"/><path class="qj-xzs08j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shop-scale" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ip2emh-hq) {
  d: path("M16 5.75h3m-1.5 3v5.5m-14.75-3h10.5m-5.25 0v3");
}

:global(.jh2trtb0z) {
  width: 18.5px;
  height: 7px;
  x: 2.75px;
  y: 14.25px;
  rx: 2px;
}

:global(.jolwk_1dx) {
  width: 7.5px;
  height: 6px;
  x: 13.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.qj-xzs08j) {
  d: path("M6 17.75h3");
}

</style>
