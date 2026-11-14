<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjouhj-xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:valve-oil" {...props}></Icon>
<style>
:global(.kjouhj-xa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10h10v11.5H7Zm3 0h4l-1.25-5.5h-1.5Zm2-5.5v-2m-2.5 13h5");
}

</style>
