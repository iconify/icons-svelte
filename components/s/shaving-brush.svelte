<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e73t7cbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shaving-brush" {...props}></Icon>
<style>
:global(.e73t7cbts) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12C6 9 7.5 3.5 12 3.5S18 9 16.5 12Zm2 0h5v2.5h-5ZM8 14.5h8V21H8Z");
}

</style>
