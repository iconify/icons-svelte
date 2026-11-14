<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg-uy1bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skylight-flat" {...props}></Icon>
<style>
:global(.wg-uy1bvf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h17v8.5h-17ZM8 8.25h8V12H8Zm4-5.75v2.25m-5-1L8.25 5M17 3.75L15.75 5");
}

</style>
