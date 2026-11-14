<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v94kz5_pm"/><path class="zq3eisuht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tenant" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v94kz5_pm) {
  d: path("M3.5 21.5V4A1.5 1.5 0 0 1 5 2.5h9A1.5 1.5 0 0 1 15.5 4v17.5");
}

:global(.zq3eisuht) {
  d: path("m17.557 3.323l2 .8a1.5 1.5 0 0 1 .943 1.393v12.968a1.5 1.5 0 0 1-.943 1.393l-2 .8a1.5 1.5 0 0 1-2.057-1.393V4.716a1.5 1.5 0 0 1 2.057-1.393M2.5 21.5h19M7 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-.75 13c0-3.75 1.5-6.25 3.25-6.25s3.25 2.5 3.25 6.25");
}

</style>
