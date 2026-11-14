<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_sz0cjkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sort-amount-up" {...props}></Icon>
<style>
:global(.g_sz0cjkw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 20V4m-3 3l3-3l3 3m3-3H16v2.5h-3.5Zm0 6.75h6v2.5h-6Zm0 6.75H21V20h-8.5Z");
}

</style>
