<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5n0nyber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:safety-goggles" {...props}></Icon>
<style>
:global(.x5n0nyber) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h18v5c0 2-1.5 3-3 3h-2.5l-2-2.5h-3l-2 2.5H6c-1.5 0-3-1-3-3Zm3.5 3h2m7 0h2");
}

</style>
