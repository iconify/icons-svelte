<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsw7ryb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stock-sell" {...props}></Icon>
<style>
:global(.fsw7ryb8h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5v16M11.5 5v15.5m6-17.5v8.5M4.5 7h3v8h-3ZM10 8.5h3v7h-3Zm6-3.75h3v4.5h-3ZM15 18h6");
}

</style>
