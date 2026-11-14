<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alkvzgbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shift-night" {...props}></Icon>
<style>
:global(.alkvzgbsg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 14.5A8.5 8.5 0 1 1 9.5 4A6.75 6.75 0 0 0 20 14.5Zm-2-9h.01M21 9h.01");
}

</style>
