<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcvfr7ydp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:temperature-excursion" {...props}></Icon>
<style>
:global(.gcvfr7ydp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 14.5V5a2 2 0 0 1 4 0v9.5a3.75 3.75 0 1 1-4 0ZM12 8v6m4-8l3-3l2.5 3");
}

</style>
