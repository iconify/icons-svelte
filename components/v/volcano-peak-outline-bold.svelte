<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wa1c01bfg"/><path class="zgtvbjo0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:volcano-peak-outline-bold" {...props}></Icon>
<style>
:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wa1c01bfg) {
  d: path("m4 20 7 -7h3l7 7Z");
}

:global(.zgtvbjo0h) {
  d: path("m9 10 3 -3 3 3");
}

</style>
