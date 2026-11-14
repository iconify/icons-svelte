<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk2qa67_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:subscript" {...props}></Icon>
<style>
:global(.nk2qa67_b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6L12 17m0-11L3.5 17m12-1c0-1.25 1-2 2.25-2s2.25.75 2.25 2c0 2-4.5 3-4.5 5H20");
}

</style>
