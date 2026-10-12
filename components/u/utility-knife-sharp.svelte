<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8vft3vck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:utility-knife-sharp" {...props}></Icon>
<style>
:global(.s8vft3vck) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9 9.5l11.25-.75h1v8.5h-1L9 16.5Zm0 1.25H6.25l-3.5 4H9ZM12 13h6.5");
}

</style>
