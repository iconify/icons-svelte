<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="omou6bb8f"/><path class="eslw69b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:speciation" {...props}></Icon>
<style>
:global(.eslw69b8c) {
  d: path("M17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.omou6bb8f) {
  d: path("M12 21.5V14c0-4-3-5-5.5-7.5M12 14c0-4 3-5 5.5-7.5M3 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
