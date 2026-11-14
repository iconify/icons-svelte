<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3g8ovb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:soccer-clean-sheet" {...props}></Icon>
<style>
:global(.h3g8ovb3w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19V5h18v6.8M3 19L17 5M3 10l7.92 7.92M9 5l9.405 9.405M14.75 18l2 2L21 15.75");
}

</style>
