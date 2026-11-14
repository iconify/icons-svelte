<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1uleqyqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skier-snowplough" {...props}></Icon>
<style>
:global(.n1uleqyqr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 3.5v5M8 19l4-6.5l4 6.5m-9-8l5-2.25L17 11M4.5 15l6 6m9-6l-6 6");
}

</style>
