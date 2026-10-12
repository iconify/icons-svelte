<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rxmjt93pl"/><path class="afcbyfzfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:thumbtack" {...props}></Icon>
<style>
:global(.afcbyfzfu) {
  d: path("M5.75 17.5h7M9.8 5.5a6 2.75 30 1 0 10.4 6a6 2.75 30 1 0-10.4-6m3.8 5.4l-1 1.7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rxmjt93pl) {
  width: 13px;
  height: 7.5px;
  x: 2.75px;
  y: 13.75px;
  rx: 1.5px;
}

</style>
