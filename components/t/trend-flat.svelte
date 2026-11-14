<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="utv5lsbwt"/><path class="gcrmkqbmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trend-flat" {...props}></Icon>
<style>
:global(.gcrmkqbmq) {
  d: path("m17.5 9.5l3 3l-3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.utv5lsbwt) {
  d: path("m3 13.5l4.5-4l4 3h9");
}

</style>
