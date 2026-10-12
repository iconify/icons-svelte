<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sr_0fj4cl"/><path class="nk73kvqig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:subscribe-button" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nk73kvqig) {
  d: path("M7.25 10v4m-2-2h4m2-1.25h6.5m-6.5 2.5h4");
}

:global(.sr_0fj4cl) {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 7px;
  rx: 5px;
}

</style>
