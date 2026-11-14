<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jemsqfbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:supersonic-jet" {...props}></Icon>
<style>
:global(.jemsqfbba) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 15h10.5l6-1.25l-6-1.25H9l-3.5-5H3.75L3.5 13c0 1.25.5 2 1.5 2Zm2.5 0H15v2.25H7.5Z");
}

</style>
