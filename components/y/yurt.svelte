<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="adc5w46wu"/><path class="xqrf9bb2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:yurt" {...props}></Icon>
<style>
:global(.adc5w46wu) {
  d: path("M3.5 20.5V13c0-5 4-7.5 8.5-7.5S20.5 8 20.5 13v7.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xqrf9bb2q) {
  d: path("M9.5 20.5V15h5v5.5M12 5.5V3");
}

</style>
