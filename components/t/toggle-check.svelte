<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_axcacrg"/><path class="ma2tgdb5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:toggle-check" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ma2tgdb5l) {
  d: path("M13 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-7.25 0L7 13.25l2.25-2.5");
}

:global(.n_axcacrg) {
  d: path("M8 6.5h8a5.5 5.5 0 0 1 5.5 5.5a5.5 5.5 0 0 1-5.5 5.5H8A5.5 5.5 0 0 1 2.5 12A5.5 5.5 0 0 1 8 6.5");
}

</style>
