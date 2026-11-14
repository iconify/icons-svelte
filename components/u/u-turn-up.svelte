<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h9yvmub8g"/><path class="r10uzdh1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:u-turn-up" {...props}></Icon>
<style>
:global(.h9yvmub8g) {
  d: path("M4.5 3.5V14a5.5 5.5 0 0 0 11 0V3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r10uzdh1b) {
  d: path("m12 7l3.5-3.5L19 7");
}

</style>
