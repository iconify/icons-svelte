<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6i3nwbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:small-cell" {...props}></Icon>
<style>
:global(.g6i3nwbuz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5h5v7h-5Zm2.5 7v9.5M6.75 6q-1.5 2.5 0 5M4 4q-2.5 4.5 0 9m13.25-7q1.5 2.5 0 5M20 4q2.5 4.5 0 9");
}

</style>
