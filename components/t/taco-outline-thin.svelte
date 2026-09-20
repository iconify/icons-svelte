<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zc40vp7yl"/><path class="c6yqvq36o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:taco-outline-thin" {...props}></Icon>
<style>
:global(.c6yqvq36o) {
  d: path("M5 11c2 -3 4 -1 7 -3s5 1 7 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zc40vp7yl) {
  d: path("M4 11c0 5 3 8 8 8s8 -3 8 -8Z");
}

</style>
