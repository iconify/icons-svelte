<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c32qphw7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:solid-shapes" {...props}></Icon>
<style>
:global(.c32qphw7n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5h8v8H3Zm10 4a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-1-13l5 7.5H7Z");
}

</style>
