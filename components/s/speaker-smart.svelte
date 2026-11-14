<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-a_1k4oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:speaker-smart" {...props}></Icon>
<style>
:global(.z-a_1k4oj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3h7a3 3 0 0 1 3 3v12.5a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3Zm-3 5.5h13M9 13h6m-6 3.5h6");
}

</style>
