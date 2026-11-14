<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_-f959yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smoothie-cup" {...props}></Icon>
<style>
:global(.u_-f959yk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11h10l-1 10H8ZM6 8.5h12V11H6Zm1.5 0c0-2.5 2-4 4.5-4s4.5 1.5 4.5 4m-3.25-3.75l2.25-2.5");
}

</style>
