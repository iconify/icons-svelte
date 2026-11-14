<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aibou09ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:swimmer-butterfly" {...props}></Icon>
<style>
:global(.aibou09ci) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.5 3.5q-3.5-12-6-6m13 6q3.5-12 6-6M3 17q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
