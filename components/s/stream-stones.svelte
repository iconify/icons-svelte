<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyric724a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stream-stones" {...props}></Icon>
<style>
:global(.kyric724a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5H7v3H2.5Zm7.25 0h4.5v3h-4.5Zm7.25 0h4.5v3H17Zm-14-4q2.25-1.75 4.5 0t4.5 0t4.5 0t4.5 0m-18 11q2.25-1.75 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
