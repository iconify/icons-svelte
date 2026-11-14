<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_6_ypb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tsunami-zone" {...props}></Icon>
<style>
:global(.d_6_ypb2b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5c5 0 6.5-4 6.5-7.5c0-4.5 3.5-7.5 7.5-7.5c2.75 0 5 2 5 4.5c0 2-1.5 3.25-3 3.25s-2.5-1-2.5-2.5M2.5 21.5h10m5.5-6.75v3.5M18 21h.01");
}

</style>
